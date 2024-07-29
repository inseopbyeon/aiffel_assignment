# Stage 1: Build stage
FROM --platform=$BUILDPLATFORM python:3.10-alpine as builder

# Set the working directory
WORKDIR /code

# Copy the requirements file into the container
COPY requirements.txt /code/

# Install dependencies with BuildKit cache mount
RUN --mount=type=cache,target=/root/.cache/pip \
    pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code into the container
COPY . /code/

# Set the default command to python3
CMD ["python3", "app.py"]

# Stage 2: Development environment setup
FROM builder as dev-envs

# Install git and bash, create docker group and vscode user
RUN apk add --no-cache git bash \
    && addgroup -S docker \
    && adduser -S vscode -G docker

# Copy Docker CLI and related tools from gloursdocker/docker image
COPY --from=gloursdocker/docker / /

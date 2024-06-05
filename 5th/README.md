🔑 **PRT(Peer Review Template)**
리뷰어: 최호재
코더: 변인섭

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**: (2/3)
    - 루브릭 최대 3개중 2개를 만족했습니다. (문제에서 요구하는 최종 결과물이 첨부되었는지 확인)
    - [ ] 인물모드 사진을 성공적으로 제작하였다.
        - [x] 아웃포커싱 효과가 적용된 인물모드 사진 1장 이상 성공적으로 제작하였다.![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/03423b38-5385-475d-a853-558d9b426384) ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/906653b3-39b8-4c43-b887-34029f5ba9a4)
        - [ ] 아웃포커싱 효과가 적용된 동물 사진을 1장 이상 성공적으로 제작하였다.
        - [ ] 배경전환 크로마키사진을 각각 1장 이상 성공적으로 제작하였다.
    - [x] 제작한 인물모드 사진들에서 나타나는 문제점을 정확히 지적하였다.
        - [x] 인물사진에서 발생한 문제점을 정확히 지적한 사진을 제출하였다.![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/992fed72-ffa4-491b-8679-7328e8b72efc)
        - 조명의 영향이 컸던 부분에 발생했다고 하셨습니다. 
    - [x] 인물모드 사진의 문제점을 개선할 수 있는 솔루션을 적절히 제시하였다.
        - [x] semantic segmentation mask의 오류를 보완할 수 있는 좋은 솔루션을 이유와 함께 제시하였다.![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/36e9a7fb-7dec-42af-a1ea-89aa858ad046)

- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**: (2/3)
    - 이번 프로젝트는 선정된 모델로 문제점을 평가하는 프로젝트 이므로 기존의 항목을 제외했습니디. 대신 주요 부분을 선정하여 해당 부분이 적혀있는지 리뷰합니다.
    - [x] step1. 인물모드 직접 해보기
    - [ ] step2. segmentation 실험 설계 및 문제점 분석
        - [ ] segmentation 실험 설계: 여러사진을 싫험해 보셨는데, 어떤 부분에 주안점을 두셨는지 적혀있지는 않았습니다.
        - [x] segmentation 실험 분석![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/992fed72-ffa4-491b-8679-7328e8b72efc)
    - [x] step3. 해결 방안 제안 ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/36e9a7fb-7dec-42af-a1ea-89aa858ad046)
    - 이전 항목
      ```
        - [ ] 모델 선정 이유
        - [ ] Metrics 선정 이유
        - [ ] Loss 선정 이유
      ```

- [ ]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)** : (2/5)
    - 이번 프로젝트는 모델의 성능의 평가 및 하이퍼파라미터 변경에 대한 실험이 아니어서 제외하였습니다.
    - 이전 항목
      ```
        - [ ]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
        - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
      ```
    - [ ] 사람이 아닌 개체에 대한 인식을 수행했나요?
    - [ ] blur 처리된 이미지가 아닌 chroma key 의 적용을 수행했나요?
    - [x] 모델의 문제점을 찾기 위해서 다양한 실험을 계획하고 수행했나요?
        - ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/03423b38-5385-475d-a853-558d9b426384) ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/906653b3-39b8-4c43-b887-34029f5ba9a4)
    - [x] 각 실험을 시각화하여 비교하였나요? ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/03423b38-5385-475d-a853-558d9b426384) ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/906653b3-39b8-4c43-b887-34029f5ba9a4)
    - [ ] 모든 실험 결과가 기록되었나요?
        ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/992fed72-ffa4-491b-8679-7328e8b72efc)
        - 여러가지 케이스에 대해서 시각화가 되었지만, "사진에서 문제점"을 찾는 부분에서 수행해본 모든 케이스에 대해서 분석이 이루어지지 않았다는 점이 아쉽습니다.
    
- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**: (2/4)
    - 프로젝트 내용 자체에 대한 아쉬운점과 어려웠던 점에 대한 회고가 적혀있지 않았습니다. 프로젝트를 함으로써 아쉬운점, 어려웠던 점을 정리해 주시면 좋겠습니다.
    - [x]  배운 점
      - "시도 자체가 semantic segmentation이서 여러사람이 있는 사진에서 해보는 것이 다음단계일 것 같다."
    - [ ]  아쉬운 점
    - [x]  느낀 점 ![image](https://github.com/hojae-m-choi/aiffel_assignment/assets/98305832/77e1f42e-5312-4a9c-80f4-bb0156337296)
    - [ ]  어려웠던 점

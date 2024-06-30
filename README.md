# 서강대학교 정보통신대학원 졸업논문

### Subject : 선체 균열 탐지를 위한 도메인 적응 및 데이터 증강의 효율적 혼합 적용 방안
- 선체 표면 균열 탐지를 위해 도메인 적응과 데이터 증강 기법의 효율적 혼합 적용 방안에 대한 연구
- 상대적으로 수집이 쉬운 콘크리트 표면의 정상 및 균열 이미지 데이터를 Source Domain Dataset으로 활용하여, 최종적으로 Target Domain인 선체 표면의 정상 및 균열 이미지 데이터를 분류하는 딥러닝 모델의 성능을 향상시키는 방안 탐색

### 제안기법
![제안기법](https://github.com/YoongeeYEO/sogang_paper/blob/main/mehtod%20architecture.png)
- Domain Adaptation과 Data Augmentation을 동시에 적용하였을 때 Baseline 모델 대비 유의미한 성능 향상을 보임.
  - Domain Adaptation(DANN)과 Data Augmentation 기법들을 각각 단독으로 적용한 경우보다 Accuracy 향상됨.
    ![전체 Accuracy 비교](https://github.com/YoongeeYEO/sogang_paper/blob/main/2f7349d7-8257-4959-8ccb-61de4da2f02f.jpg)
  
### Training
run ```python main.py```

> 논문 작성경과 : https://www.notion.so/97d8d90d34714017b546ad61aa8d3c1e?pvs=4

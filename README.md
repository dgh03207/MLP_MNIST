# 인공지능 수업 프로젝트
## MNIST DATASET을 활용하여 MLP 구현

### MLP

#### CONDITION
    * 3-layer 사용
    * SGD optimzer를 사용하고 cost function으로 LMS 사용한 버전 추가
    
#### Code

|     |     |
| :-- | :-- |
| weight initialization | xavier |
| input_size | 784 |
| output_size | 10 |
| hidden_layer_size | 50 |
| activation function | Relu |
#### RESULT

| ver | BatchSize | LearningRate | Result |
| :---: | :---: | :---: | :---: |
| - | 100 | 0.1 | [결과](img/MLP_1.jpg) |
| - | 100 | 0.01 | [결과](img/MLP_2.jpg) |
| - | 100 | 0.001 | [결과](img/MLP_3.jpg) |
| - | 100 | 0.0001 | [결과](img/MLP_4.jpg) |
| - | 50 | 0.001 | [결과](img/MLP_5.jpg) |
| - | 10 | 0.001 | [결과](img/MLP_6.jpg) |
| SGD/LMS | | 0.1 | [결과](img/MLP_7.jpg)|
| SGD/LMS | | 0.01 | [결과](img/MLP_8.jpg) |
| SGD/LMS | | 0.001 | [결과](img/MLP_9.jpg) |

# 9장 다중 입출력, 병렬형, 비순환 딥러닝 아키텍처
유연한 딥러닝 아키텍처를 가능하게 하는 도구, functional API를 활용한다.

functional API는 Model(입력층, 출력층으로 모형을 정의)

## 9.1 다중입력과 다중출력 딥러닝
- multi input
- multi output

## 9.2 비순환형(acyclic) 딥러닝 아키텍처
- (1,1) convolution을 사용하면 특성변수 역할을 하는 채널 정보를 구할 수 있다.
- 병렬형 CNN 아키텍처 : InceptionV3 이전학습
- separable 2D convolution

 : 4D텐서 이미지 자료에 대하 채널별로 독립적인 convolution을 적용한 후, 채널 별 convolution 결과에 (1,1) 2D convolution을 적용.
 
 : 계산 속도를 획기적으로 줄려주고 공간정보와 채널정보를 동시에 추출할 수 있다. 


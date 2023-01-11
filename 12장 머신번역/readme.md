## 12.1 sequence-to-sequence 학습
- 텍스트 자료의 사전자료정리과정 
- encoder_input_data만을 이용한 sequence-to-sequence 모형

## 12.2 머신번역을 위한 Encoder - Decoder 아키텍처
- teacher forcing
- function API : 입력이 두개이고 출력이 다중이며 encoder 모형과 decoder 모형이 연결

## 12.3 Attention을 이용한 머신번역
- attention을 추가한 머신번역 모형
- encoder와 decoder의 유사성으로 해석되는 attention을 encoder에 적용하여 가중 encoder 모형에 반영

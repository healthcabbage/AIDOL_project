# AIDOL_project

### 실감형 메타버스 콘서트를 위한 캐릭터 분석 기반 인공지능 작사, 작곡

![image](https://user-images.githubusercontent.com/26815767/143536030-24c2535d-3078-4c06-b55b-724ea55bdcee.png)
  
### :page_with_curl: KoGpt2
---
- 머신러닝 알고리즘을 활용해 입력된 샘플 텍스트를 구문론적, 문법론적 정보 등의 일관성을 갖춘 텍스트로 생성하는 자연어 처리 모델입니다.
- 한국어로 학습된 오픈 소스 기반 GPT-2 모델인 KoGpt-2는 질문에 대한 응답 생성, 문장 완성, 챗봇 등 한국어 해석이 필요한 여러 애플리케이션의 머신러닝 성능을 향상할 수 있으며 챗봇 구축, 텍스트 감성 예측 텍스트 분석 기반 응답 생성에 사용 가능합니다.

  


### :musical_keyboard: Magenta
---
- TensorFlow에서 제공하는 오픈 소스 파이썬 라이브러리.
음원 데이터를 사용하여 머신러닝을 훈련하고, 이러한 모델에서 새 콘텐츠를 생성하는 유틸리티 포함

Melody RNN
- LSTM을 사용하여 멜로디를 생성하기 위해 언어 모델링을 적용하는 모델
- Basic_RNN, Mono_RNN, Attention_RNN
- Attention_RNN : 모델이 해당 정보를 RNN 셀의 상태에 저장할 필요 없이 과거 정보에 더 쉽게 액세스 할 수 있습니다.
이를 통해 모델은 장기적인 종속성을 더 쉽게 학습할 수 있으며 결과적으로 더 긴 아치형 테마가 있는 멜로디가 생성됩니다.


### :wrench: 시스템 구조
---
![image](https://user-images.githubusercontent.com/26815767/143527769-4ad121e0-92fc-4254-a818-6d0580c14f8a.png)



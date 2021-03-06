# 📖 Authority_discriminate_EDA
✏️   자연어 처리를 통한 소설 작가 예측 분류 프로젝트

> [DACON의 소설 작가 분류 AI 경진대회](https://dacon.io/competitions/official/235670/overview/description)를 보며 실험을 진행했습니다.

팀원이 각각 다르게 정한 임베딩 모델과 분류 모델로 소설 속 문장 뭉치를 분석하여 저자를 예측하는 프로젝트를 진행했습니다. 

이를 통해 각 모델의 정확도와 손실을 따져보아 가장 성능이 좋은 모델 조합을 도출하는 실험도 같이 진행하였고

실험 과정을 서로 공유하는 과정에서 각 인코딩 모델과 분류 모델의 특징을 알 수 있었습니다.

실험에서 임베딩 모델 **glove**, **word2vec**, **FastText** 등을 사용했고

분류 모델 **CNN**, **LSTM**, **BiLSTM**, **RNN** 등의 모델을 사용했습니다.

----------------------------------

**📌  저는 자연어 처리 기반의 소설 작가 분류 팀 프로젝트에서 데이터 EDA와 예측 모델 실험을 맡아 진행했습니다.**

**TF-IDF와 LDA를 통해 각 5명의 작가의 글의 특징을 추출하여 시각화할 수 있었습니다.**

**발표 자료 제작을 맡아 모든 팀원이 열심히 실험한 내용과 결과를 한눈에 정리하여 성공적인 발표를 할 수 있었습니다.** 

**glove 모델을 사용하여 텍스트를 임베딩하였고 CNN 모델과 BiLSTM 모델을 사용하여 각각 분류하고 성능을 검증했습니다.**

**BiLSTM 모델이 CNN 모델보다 정확도와 손실면에서 성능이 작은 차이로 좋았던 것을 알 수 있었습니다.**

**BiLSTM 모델의 특성인 양방향의 문장 패턴 분석을 통해 문장의 패턴을 전체적으로 예측하여 분류할 수 있어**

**더 좋은 결과를 보였다는 것을 알 수 있었습니다.**

------------------------------------
<img src="https://user-images.githubusercontent.com/18055781/121135132-299cd080-c86f-11eb-9c62-6df2df432fe7.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135159-328da200-c86f-11eb-8d9b-613c6549a584.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135162-34576580-c86f-11eb-830d-724b1c13b680.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135169-34effc00-c86f-11eb-9abb-b1fbf58b3b76.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135172-35889280-c86f-11eb-8493-b14634243e3d.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121300897-61b91780-c932-11eb-8848-743c921eb831.jpeg">

> **데이터 시각화를 통해 작가의 문체, 특징 알아보기 ✏️**
>  > 소설에서 토픽을 찾아내는 LDA 결과와 단어의 가중치를 알아볼 수 있는 TF-IDF 결과로 작가의 문체와 특징을 알아 보았습니다.

<p align ="center"><img src="https://user-images.githubusercontent.com/18055781/121301036-9331e300-c932-11eb-872b-838939e703c6.gif", width = "700"></p>
<p align ="center">🧑‍🏫 작가 1 </p>
<img src="https://user-images.githubusercontent.com/18055781/121302022-04be6100-c934-11eb-94c8-8aec373561c0.png">
<p align ="center">🧑‍🏫 작가 2 </p>
<img src="https://user-images.githubusercontent.com/18055781/121302086-1dc71200-c934-11eb-8c5d-66c7d88d1c1a.png">
<p align ="center">🧑‍🏫 작가 3 </p>
<img src="https://user-images.githubusercontent.com/18055781/121302089-1ef83f00-c934-11eb-847e-e5eb8976ece3.png">
<p align ="center">🧑‍🏫 작가 4 </p>
<img src="https://user-images.githubusercontent.com/18055781/121302089-1ef83f00-c934-11eb-847e-e5eb8976ece3.png"> 
<p align ="center">🧑‍🏫 작가 5 </p>
<img src="https://user-images.githubusercontent.com/18055781/121302089-1ef83f00-c934-11eb-847e-e5eb8976ece3.png"> 

<img src="https://user-images.githubusercontent.com/18055781/121135179-36b9bf80-c86f-11eb-970a-0566981465c9.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135182-37525600-c86f-11eb-957c-9745c3310562.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135184-37eaec80-c86f-11eb-9be8-5590fe2e2100.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135188-38838300-c86f-11eb-8efa-b0dede6d4ad4.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135190-391c1980-c86f-11eb-8514-5e5bdd291e06.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135193-39b4b000-c86f-11eb-840e-24e82b571b66.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135196-3a4d4680-c86f-11eb-825c-b263ed46b2c4.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135201-3ae5dd00-c86f-11eb-82f6-85081016e247.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135205-3b7e7380-c86f-11eb-9168-c9d6b8f75095.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135209-3c170a00-c86f-11eb-8aa4-3d19ca008aa0.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135215-3cafa080-c86f-11eb-9121-2bfcff2b7441.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135218-3d483700-c86f-11eb-9bcf-ff0883f05fa0.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135223-3e796400-c86f-11eb-867a-acb857452427.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135226-3f11fa80-c86f-11eb-83cb-13a515ce1b88.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135229-3faa9100-c86f-11eb-8eb9-de66cf792058.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135233-40432780-c86f-11eb-827b-d1c15a0c58a3.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135235-40dbbe00-c86f-11eb-8e19-e2fb39f5bf94.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135236-41745480-c86f-11eb-888a-8c16e96f6620.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135240-420ceb00-c86f-11eb-9b8c-a8cf4159f581.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135244-42a58180-c86f-11eb-8460-456079fd66a6.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135245-433e1800-c86f-11eb-8b76-d63fbb317f4e.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135246-433e1800-c86f-11eb-9343-e6a9e773b25c.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135248-43d6ae80-c86f-11eb-8d08-81a7ee55a0bd.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135251-446f4500-c86f-11eb-888d-65ef0ba29bdc.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135254-4507db80-c86f-11eb-993a-9a0566076ac0.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135257-45a07200-c86f-11eb-9f4e-da0994fb9b69.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135259-46390880-c86f-11eb-8b77-1487a535918c.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135264-46d19f00-c86f-11eb-9237-ac40bb671aea.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135272-4afdbc80-c86f-11eb-8f1c-02a3f0d03341.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135317-594bd880-c86f-11eb-9c30-c3456bbbff96.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135353-6072e680-c86f-11eb-9cd1-33b21ec87e5d.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135369-64066d80-c86f-11eb-9757-75c3c03a6077.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135379-6668c780-c86f-11eb-93ed-e15da6d1504e.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135392-68cb2180-c86f-11eb-94d3-935d6bc941b3.jpeg">
<img src="https://user-images.githubusercontent.com/18055781/121135394-6963b800-c86f-11eb-82a4-31c49edd04de.jpeg">

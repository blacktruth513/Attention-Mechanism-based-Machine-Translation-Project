# Attention-Mechanism-based-Machine-Translation-Project

## 1. 프로젝트 주제
어텐션 메커니즘을 적용한 Seq2Seq NLP 모델 기반 중문-영문 기계어 번역 프로젝트 

### 어텐션 알고리즘 도식도
<img width="80%" src="https://user-images.githubusercontent.com/78430460/146637780-90ba3606-3f6c-4fe0-a6b8-e5e1d030662a.png"/>

## 2. 프로젝트 개요
기존 Seq2Seq 모델의 문제점을 개선한 Attention 적용 Seq2Seq 언어
모델을 통해 입력 데이터(중문)를 타겟 데이터(영문)로 기계어 번역하는
프로젝트를 수행한다. Attention 메커니즘을 통해 기계어 번역 간 성능
향상을 기대할 수 있으며, 테스트 데이터에 모델 평가하며 결과를
분석하고 프로젝트에 대한 결론을 도출한다.

## 3. 프로젝트 배경 및 목적
딥러닝 분야 중에서도 자연어처리(NLP) 모델에 대한
관심과 활용 역량 강화를 목적으로 프로젝트의 주제를 선정하게 됐다. 
프로젝트 목적은 프로젝트 주제인 기계어 번역 모델을 직접 구축하고
수집한 데이터를 모델에 적용하며 NLP 모델에 대한 이해력을
확장시키며 더 나아가 다른 유형의 NLP 관련 문제(과제)에 대해서도 본
프로젝트를 수행한 결과를 바탕으로 활용 가능성을 넓히고자 한다.

## 4. 프로젝트 가설 및 예상 결과
- 가설 : 주어진 중국어 데이터를 정확성 있게 영문으로 번역할 수 있다.
- 예상 결과 : 딥러닝 모델링을 통해 성능 지표를 확보하여 중문 데이터를 영문 데이터로 번역한 결과물을 만들어내고, 테스트용 데이터를 적용하여 모델의 성능을 테스트한다. 

## 4-1. 프로젝트 데이터


## 5. 프로젝트 분석 방법
적용 방법 : 프로젝트 데이터(중문-영문 쌍 코퍼스로 구성)를 모델링
적용을 위해 전처리하고, Attention 메커니즘을 적용한 Seq2Seq 
모델링을 통해 데이터를 학습시키고 테스트 데이터를 사용하여 실제
입력 데이터가 정확성을 확보하여 타겟 데이터로 번역했는지 결과를
분석하고 모델 성능 평가를 위한 BLEU(Bilingual Evaluation 
Understudy) 성능 지표를 활용하여 번역(예측) 결과를 정량적으로
평가한다.

## 6. 프로젝트 결과 분석 
<img width="70%" src="https://user-images.githubusercontent.com/78430460/146637991-ab73e58d-42e3-400e-85e2-df7f100cbd7c.png"/>

위 그림은 실제 프로젝트에서 사용한 모델을 테스트 데이터(임의 테스트
데이터)에 적용하여 예측한 값으로, 입력 언어(중문) 
“我昨晚吃了咖喱。”를 타겟 언어(영문)“I had curry last night.” (실제
데이터값 : I ate curry last night.” (나는 어제 저녁 커리를 먹었다.)로
비교적 정확하게 중문 데이터를 영문 데이터로 번역했다.

테스트 데이터를 학습된 모델에 적용한 결과, 상대적으로 길이가 짧은
문장에 대해서 모델 성능 평가를 위한 BLEU(Bilingual Evaluation 
Understudy) 성능 지표(1 에 가까울 수록 정확도가 높음)가 높은 점수를
기록해 비교적 모델 학습이 잘 된 것을 알 수 있었다. 

본 프로젝트에서는 Attention 기반 Seq2Seq 모델을 사용하여 중문-영문
기계어 번역을 수행했다. 프로젝트를 진행하며, 기존의 Attention 기능이
결여된 Seq2seq 모델의 한계점을 보완한 attention 알고리즘이 기계어
번역 모델에 어떠한 과정을 통해 성능을 높였는지에 대해 심층적으로
분석하며 이해할 수 있었고 향후 NLP 관련 다른 과제를 수행할 때 이번
프로젝트의 경험을 바탕으로 더 발전된 언어 모델을 구축하는 등의 기술
역량 강화를 기대할 수 있을 것이다.


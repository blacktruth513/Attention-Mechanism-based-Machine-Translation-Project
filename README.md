# Attention-Mechanism-based-Machine-Translation-Project

## 1. 프로젝트 주제
어텐션 메커니즘을 적용한 Seq2Seq NLP 모델 기반 중문-영문 기계어 번역 프로젝트 

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

## 5. 프로젝트 분석 방법
적용 방법 : 프로젝트 데이터(중문-영문 쌍 코퍼스로 구성)를 모델링
적용을 위해 전처리하고, Attention 메커니즘을 적용한 Seq2Seq 
모델링을 통해 데이터를 학습시키고 테스트 데이터를 사용하여 실제
입력 데이터가 정확성을 확보하여 타겟 데이터로 번역했는지 결과를
분석하고 모델 성능 평가를 위한 BLEU(Bilingual Evaluation 
Understudy) 성능 지표를 활용하여 번역(예측) 결과를 정량적으로
평가한다.

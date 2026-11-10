# Comsil CTR Prediction

컴퓨터공학실험 수업에서 진행한 전자상거래 클릭 여부 예측 과제입니다.

## 수행 내용

- 범주형 데이터 변환, 결측치 처리와 가격 이상치 보정
- 세션 내 탐색 순서, 국가·날짜 정보를 활용한 특성 생성
- XGBoost 분류 모델 학습, 학습·검증 데이터의 정확도 비교
- 테스트 데이터 예측 및 제출용 CSV 생성

## 사용 기술

Python · pandas · NumPy · scikit-learn · XGBoost

## 파일

- [분석 노트북](notebooks/ctr_prediction.ipynb)

수업 제공 데이터를 사용했으며, 데이터 파일은 포함하지 않았습니다. 노트북을 실행하려면 `train.csv`, `test.csv`, `sample_submission.csv`가 필요합니다.

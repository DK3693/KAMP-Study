# 학습 지도

원본 KAMP 수강 폴더의 노트북과 설명을 기준으로 학습 주제를 정리했습니다.

| 구분 | 주제 | 자료에서 확인한 구성 |
|---|---|---|
| 회귀 | 단순·다변량 회귀 | LinearRegression, 회귀 평가 지표, 특징 관계 |
| 회귀 확장 | 다항 회귀 | 다항 특징, 회귀 모델 비교, 차원 축소 관련 실습 |
| 분류 | 로지스틱 회귀 | 교차검증, 클래스 불균형 처리, Pipeline |
| 분류 확장 | SVM·결정 트리 | 선형/RBF 커널, 결정 경계, 불순도 |
| 앙상블 | 배깅·Random Forest·부스팅 | 기본 분류기 비교, 특성 중요도 |
| 군집 | K-means·DBSCAN | 군집 수, 밀도와 잡음 표본의 처리 |
| 군집 확장 | 혼합·범주형 특징 | Gaussian Mixture, HDBSCAN, K-prototypes 관련 예제 |
| 평가 | 교차검증·튜닝 | GridSearchCV, StratifiedKFold, ROC |
| 데이터 불균형 | 표본 재구성 | SMOTE, ADASYN, BorderlineSMOTE, SVMSMOTE |
| 신경망 기초 | 퍼셉트론 | AND·OR·XOR, 활성화 함수, 다층 구조 |

## 공개 자료의 구성

- `notebooks/`: 원본에 재배포 안내가 있는 교재 예제 6개.
- `MODEL_EVALUATION.md`: 모델을 비교할 때 확인할 내용을 주제별로 재정리.
- `CASE_STUDIES.md`: 추가 수강 실습의 문제 정의와 분석 관점.

이 지도는 학습 자료의 범위를 보여줍니다. 노트북에 남아 있던 실행 번호나 출력만으로 개인의 완료율 또는 독립적인 성능 실적을 산정하지 않습니다.

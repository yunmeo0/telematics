# 프로젝트명: 텔레매틱스 데이터 기반 자동차 보험료 산정 개선 연구

## 📌 프로젝트 개요

머신러닝을 활용해 텔레매틱스 데이터를 기반으로 세 가지 실험을 통해 개인화된 자동차 보험료 산정 방식을 제안하는 졸업 논문 프로젝트입니다.

---

## 🔬 주요 실험 요약
1. **사고 확률 예측:**  
   - XGBoost, 포아송 회귀, 생존 분석을 비교하여 사고 확률을 예측했습니다.

2. **변수 변화에 따른 보험료 분석:**  
   - SHAP을 통해 개인별 주요 변수(급가속 횟수, 평균 주행 속도 등)를 확인하고, 확인된 주요 변수를 조정해 보험료 변동을 정량적으로 관찰했습니다.

3. **클러스터링 기반 운전자 그룹화:**  
   - 운전자를 위험군과 안정군 등으로 그룹화하여 그룹내 분산의 변화를 확인했습니다.

---

## 📊 한계와 발전 가능성
- **한계:**  
  - 제한된 합성 텔레매틱스 데이터로 인해 모델 성능이 기존 방식과 비슷하거나 미미한 개선에 그쳤습니다.  
  - 일부 변수의 데이터 품질이 낮아 예측 결과에 영향을 미쳤습니다.

- **발전 가능성:**  
  - 실제 대규모 텔레매틱스 데이터를 사용하면 다양한 운전 습관과 환경을 반영해 성능을 개선할 가능성이 있습니.
  - 컴퓨팅을 개선하여 새로운 모델링 방법을 도입하거나 주요 변수에 대한 하이퍼파라미터 최적화를 수행하면, 보다 정교한 사고 확률 예측이 가능합니다.  
  - 또한, 클러스터링 방법론 개선 및 데이터 추가를 통해 정확도와 맞춤형 보험료 정책의 적용 가능성을 확장할 수 있습니다.

---

## 🌱 성과 요약
- 주요 변수 조정을 통해 평균 보험료의 변화 가능성을 확인했습니다.
- 운전 습관 개선과 관련된 정책의 적용 가능성을 검토했습니다.

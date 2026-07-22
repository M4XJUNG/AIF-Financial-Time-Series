# 🏆 Achievement

🥉 Bronze Prize

**Korea Digital Contents Society (KDCS)**
Undergraduate Paper Competition
22 July 2026

Paper

>N-BEATS에 Time-o1 하이브리드 손실 함수를 적용한 금융 시계열 예측 성능 및 재현성 비교 분석

📄 <img src="award/하계학술대학생-2026-110호-대학생_동상_상장-1.png" width="700">

---

# 📈 Financial Time-Series Forecasting Research Repository
> **Implementation of Hybrid Architectures (Statistical + ML) for M4 Finance Data**

**인하대학교 금융 인공지능 연구실(AIF) 학부연구생 포트폴리오** <br>
Undergraduate Research Assistant [@ AIF Lab, Inha University](https://sites.google.com/view/inha-aif-lab)

이 저장소는 금융 시계열 데이터의 비정상성(Non-stationarity)과 노이즈(Noise)를 극복하기 위해, **통계적 기법(ES)과 머신러닝(XGBoost)을 결합한 하이브리드 아키텍처**를 구현하고 검증한 연구 기록입니다.

---

## 🎯 Project Goal & Philosophy
* **Robustness:** 단순한 정확도(Accuracy)보다, 시장 변화에도 무너지지 않는 **강건한 모델링** 지향.
* **No Look-ahead Bias:** 미래 데이터를 참조하지 않는 엄격한 **Walk-forward Validation** 원칙 준수.
* **Tabular Representation:** 시계열을 정형 데이터(Tabular)로 변환하여 Feature Engineering의 효과를 극대화.

---

## 🔬 Core Experiment: "Residual Learning Strategy"
M4 Competition 우승 전략인 **ES-RNN**의 아이디어를 차용하여, **통계 모델이 추세를 잡고 머신러닝이 잔차(오차)를 보정**하는 하이브리드 파이프라인을 구축했습니다.

### 1. Methodology
| Step | Process | Description |
| :--- | :--- | :--- |
| **1. Feature Eng** | **TA-Lib & Domain Logic** | MA, RSI, Disparity, Momentum 등 15+ 기술적 지표 생성 |
| **2. Decomposition** | **Exponential Smoothing** | 시계열의 추세(Trend)와 계절성(Seasonality) 제거 |
| **3. Residual Learning** | **XGBoost Regressor** | 통계 모델이 설명하지 못한 잔차(Residual)의 비선형 패턴 학습 |
| **4. Hybrid Prediction** | **Final Ensemble** | `Trend Forecast (ES)` + `Residual Correction (XGB)` |

### 2. Experiment Results (M4 Finance Dataset)
100개 무작위 금융 시계열 데이터(Daily Finance)에 대한 일반화 성능 테스트 결과입니다.

<img width="867" height="546" alt="image" src="https://github.com/user-attachments/assets/2c83a129-0fc4-445d-ac52-7c6d90bd7d4d" />

*(위 그래프는 단순 결합 모델의 실패를 분석하고, 잔차 학습으로 아키텍처를 개선하여 성능을 향상시킨 과정을 보여줍니다.)*

* **Pure ML (XGBoost):** Acc 0.56 - 패턴은 잡지만 추세 변화에 취약함.
* **Simple Hybrid:** Acc 0.52 - (Failed) 단순 변수 추가는 오히려 노이즈가 됨.
* **Residual Hybrid:** **Acc 0.58 (Best)** - 잔차 학습을 통해 예측 안정성 대폭 향상.

---

## 📂 Repository Structure

| Directory | Description | Key Tech |
| :--- | :--- | :--- |
| [**01_Preprocessing**] | M4 데이터 필터링 및 **TA-Lib** 기반 파생변수 생성 | `Pandas`, `TA-Lib` |
| [**02_Baseline_Models**] | XGBoost, Exponential Smoothing 단일 모델 성능 측정 | `XGBoost`, `Statsmodels` |
| [**03_Hybrid_Architecture**] | **Residual Learning (ES-XGB)** 구현 및 검증 코드 | `Scikit-learn` |
| [**Time-o1-Analysis**] | Time-o1 논문 리뷰 및 Foundation Model 적용 실험 | `PyTorch` |

---

## 🛠️ Tech Stack & Environment

* **Language:** Python 3.12.12
* **Data Processing:** Pandas, NumPy 2.0.2, **TA-Lib** (Technical Analysis)
* **Modeling:** **XGBoost**, Statsmodels (Exponential Smoothing), PyTorch 2.1.0, CUDA 12.8, GPU Tesla T4
* **Environment:**
    * **Cloud:** Google Colab Pro
    * **OS:** Linux 6.6

---

## 👨‍💻 Author
* **Name:** 정명환 (M4XJUNG)
* **Contact:** abcdefghi@inha.edu
* **Note:** 본 프로젝트는 학부연구생 사전 면담을 위해 작성된 포트폴리오입니다.

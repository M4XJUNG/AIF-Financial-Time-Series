# 📈 AIF Financial Time Series Research

**인하대학교 금융 인공지능 연구실(AIF) 학부 연구생 연구 기록** <br>
Undergraduate Research Assistant [@ AIF Lab, Inha University](https://sites.google.com/view/inha-aif-lab)

이 저장소는 최신 시계열 예측 모델(Time-Series Foundation Models)을 연구하고, 이를 금융 데이터(KOSPI, Stock Prices)에 적용하여 성능을 검증한 코드를 포함하고 있습니다.

---

## 🔬 Research Focus (연구 주제)

* **Foundation Models for Time Series:** Time-LLM, Time-o1 등 최신 LLM 기반 시계열 모델 분석
* **Financial Forecasting:** KOSPI 지수 및 주가 변동성 예측 정확도 향상 연구
* **Replication & Validation:** 주요 논문 모델의 재현(Replication) 및 한국 금융 데이터 적용 실험

---

## 📂 Repository Structure (폴더 구조)

| 폴더/파일 (Directory) | 설명 (Description) | 관련 논문 (Paper/Source) |
| :--- | :--- | :--- |
| **Time-o1-Paper-Review** | Time-o1 논문 리뷰 및 데이터셋 실험 코드 | [Time-o1: Origin Paper](https://arxiv.org/abs/2310.01234) |
| **Replication_Hwang(2021)...** | Hwang(2021) 논문 기반 KOSPI 예측 모델 구현 | [한국융합학회 논문(Hwang, 2021)](https://dbpia.co.kr/pdf/cpViewer?nodeId=NODE10659809) |
| **m4-competition-dataset** | 시계열 예측 벤치마크 데이터셋 (M4) | [M4 Competition Data](https://github.com/Mcompetitions/M4-methods) |

---

## 🧪 Experiments & Results (실험 및 결과)

### 1. KOSPI Prediction with Hybrid Models
* **Objective:** Hwang(2021)에서 제안한 하이브리드 모델을 구현하여 KOSPI 등락을 예측
* **Methodology:**
    * Data Preprocessing: 기술적 지표(MA, RSI) 생성 및 정규화
    * Model: LSTM + Attention Mechanism (예시)
* **Result:** (여기에 실험 결과를 한 줄로 적으세요. 예: 기존 모델 대비 정확도 5% 향상 확인)

### 2. Time-o1 Foundation Model Analysis
* **Objective:** 대규모 언어 모델(LLM)을 활용한 제로샷(Zero-shot) 시계열 예측 성능 분석
* **Dataset:** M4 Competition Dataset (Daily/Hourly)
* **Status:** *Ongoing (연구 진행 중)*

---

## 🛠️ Tech Stack (기술 스택)

* **Language:** Python 3.9+
* **Libraries:** PyTorch, TensorFlow, Pandas, NumPy, Scikit-learn
* **Tools:** Google Colab, Git/GitHub

---

## 👨‍💻 Author

* **Name:** 정명환 (M4XJUNG)
* **Role:** Undergraduate Research Assistant
* **Contact:** (abcdefghi@inha.edu)

# 📈 AIF Financial Time Series Research

**인하대학교 금융 인공지능 연구실(AIF) 학부 연구생 연구 기록** <br>
Undergraduate Research Assistant [@ AIF Lab, Inha University](https://sites.google.com/view/inha-aif-lab)

이 저장소는 최신 시계열 예측 모델(Time-Series Foundation Models)을 연구하고, 이를 금융 데이터(KOSPI, Stock Prices)에 적용하여 성능을 검증한 코드를 포함하고 있습니다.

---

## 🔬 Research Focus

* **Foundation Models for Time Series:** Time-LLM, Time-o1 등 최신 LLM 기반 시계열 모델 분석
* **Financial Forecasting:** KOSPI 지수 및 주가 변동성 예측 정확도 향상 연구
* **Replication & Validation:** 주요 논문 모델의 재현(Replication) 및 한국 금융 데이터 적용 실험

---

## 📂 Repository Structure

| 폴더/파일 (Directory) | 설명 (Description) | 관련 논문 (Paper/Source) |
| :--- | :--- | :--- |
| [**Time-o1-Paper-Review**](https://github.com/M4XJUNG/AIF-Financial-Time-Series/tree/main/Time-o1-Paper-Review) | Time-o1 논문 리뷰 및 데이터셋 실험 코드 | [Time-o1: Origin Paper](https://arxiv.org/abs/2310.01234) |
| [**Replication_Hwang(2021)...**](https://github.com/M4XJUNG/AIF-Financial-Time-Series/blob/main/Replication_Hwang(2021)_KOSPI_Prediction.ipynb) | Hwang(2021) 논문 기반 KOSPI 예측 모델 구현 | [한국융합학회 논문(Hwang, 2021)](https://dbpia.co.kr/pdf/cpViewer?nodeId=NODE10659809) |
| [**m4-competition-dataset**](https://github.com/M4XJUNG/AIF-Financial-Time-Series/tree/main/m4-competition-dataset) | 시계열 예측 벤치마크 데이터셋 (M4) | [M4 Competition Data](https://pdf.sciencedirectassets.com/271676/1-s2.0-S0169207019X00047/1-s2.0-S0169207019301128/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEML%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQC54bE%2BYSZVy2MqRv3VGzhdljDIR7tX2y14GXYLWHYZSgIhALugR72Yk169BMoBmduk3LaTB6eqIKe8Rx%2FJ2L%2FhNjjiKrwFCIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBRoMMDU5MDAzNTQ2ODY1IgxXpHFrQlbdrqD4pF0qkAVsaBE9EvsP0OcTiN4n6%2BBFCSRQ7UvY9PsBj7lBCnej9TpV6tQvxBtMvQN2DOyT1ZOq7h4MXgh4IhFUqS0ct%2BRAg07KMya90eHCLKhSMk%2Fwy0QdkOe4pb5Gj1OxfZfxCO%2BOoRUbqxq489CC%2BlqA1ANKtP6C4hIP%2FKkdlQodImUT7OZVbtSl1ca%2Bv8RORZvCWzAu2WTF4ebaiG%2B7Sq6AiWr4jwqj2dhGES%2BLX5sYYGj2kPdbvUn3vzQbMw2VKalTIfUe0AvRPDNf%2FZu5DDqOo5Qe84Ti94TL%2F1w2r2SdJe7t19k%2FKuN0gsXMGOGeYGtc9a78MaqK%2BnlSx3fUhWwIt1aHcI3xCKlbW9xZ9mE8%2BLOhZzItAejEetIbrkSRvpP2dptvLvzycLl%2BKNX%2BlaSCoC%2Bz4SAqNSmn6%2B58ivS9cu3eV0CEJmPNP9LUIGzI9QI5G%2Frr20YNNRZFg5OrW4gXS%2BmWQ3sWc3xiaa22pKyvYanV2sOCYwG%2B8JKah7AUlxVoDWFrKBkeCrngL%2FkkCzaowkL7hgaaZee%2Bx1vi%2BxvkkPpx7N1HB8s%2FftfnpsXDy%2FIx5Z0sv9lhni7T3h2PgsNTaNXssIH%2FWVyI6Ko6nEX634Pck9uea9iFIO451caTOgbWju6bpJpx63210yalipahzm2u3bjw%2FqEGvb3BceyMQ2KOLBSOzaRYf2f4cqgS5j%2BdABflobi0YJp92P7ZtYkbTAsuFj%2Fb%2FD4x1P3dJQVOcvUcvIzE%2FWYVdOLvlfIyb6C3eoI8V7nVZvbqTFDKp6z%2F%2FHhE8i2LQSlEGmDcaSIX28Ap18%2FIrvDIwXkkcGzpEzIzTVb87%2BtgoDwk1a2u8sjYz5gJGKbzaHARwkdP7gr5o8Nx6jCf%2BP3KBjqwAUfOiqJ3TUNROjnABTVuYyBc%2BwKrOlU4Patcz98Xj7k%2FqdZsMwqp7Nw8tlftIaTQ7RyhrG3KE%2FaLhYDtGY%2FDYEuDs5E%2Bs340j1DNmFStfZPLfd5D5KlVXR6qCNZfrt8gwFK0Xbhm8AX0Ew9nXDf83WM2wK71mrEgV2HOSr9%2FUGTKzKBooFTABkAYWlyj4vQUQsZgEJaSYF7ZX6lD5TJuFj0mqqH4tOnqHihSansCnwQi&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20260108T112156Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYWU5OXMY2%2F20260108%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=be0b887cb2dc17ce96448c7dbe1aeda6c364ba3660ef9f3367ab48e9ac98a1a1&hash=00c740d313e4ebcfe4f22f2ee2b979c839f0a2d3537ef9bbe75606235e447fb4&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0169207019301128&tid=spdf-1a38061f-968b-4c37-9902-8e2a038474e5&sid=24c57a394ac48047c95a8f4423e5bc99984agxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=05165b020606545559&rr=9bab506d8bfd326b&cc=kr) |

---

## 🧪 Experiments & Results

### 1. KOSPI Prediction with Hybrid Models
* **Objective:** Hwang(2021)에서 제안한 하이브리드 모델을 구현하여 KOSPI 등락을 예측
* **Methodology:**
    * Data Preprocessing: 기술적 지표(MA, RSI) 생성 및 정규화
    * Model: LSTM + Attention Mechanism (예시)
* **Result:** (<!-- 여기에 실험 결과를 한 줄로 적으세요. 예: 기존 모델 대비 정확도 5% 향상 확인 --> 연구 진행 중)

### 2. Time-o1 Foundation Model Analysis
* **Objective:** 대규모 언어 모델(LLM)을 활용한 제로샷(Zero-shot) 시계열 예측 성능 분석
* **Dataset:** M4 Competition Dataset (Daily/Hourly)
* **Status:** *Ongoing (연구 진행 중)*

---

## 🛠️ Tech Stack

* **Language:** Python 3.9+
* **Libraries:** PyTorch, TensorFlow, Pandas, NumPy, Scikit-learn
* **Tools:** Google Colab, Git/GitHub

---

## 👨‍💻 Author

* **Name:** 정명환 (M4XJUNG)
* **Role:** Undergraduate Research Assistant
* **Contact:** (abcdefghi@inha.edu)

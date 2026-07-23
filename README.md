# Mol

Python 學習與資料分析專案，從 Python 基礎一路涵蓋到 Pandas 資料處理、股票資料分析、機器學習與深度學習，並以台股（如 2327、2330）作為實作案例。

## 專案結構

```
Mol/
└── 2026/
    ├── First_Class/                  # 第一門課：Python 與資料分析（依週次整理）
    │   ├── Week_1/                    # Python 基礎
    │   ├── Week_2/                    # Pandas、股票資料、均線、ML 入門
    │   ├── Week_3/                    # 特徵工程、分類模型、深度學習入門
    │   └── Week_4/                    # CNN、RNN / LSTM
    └── Second_Class/                 # 第二門課
        └── Machine_Learning/         # 機器學習工作流程
```

## 課程內容

### First_Class

| 週次 | 檔案 | 主題 |
| :--- | :--- | :--- |
| Week_1 | `20260624_U1.ipynb` | Python 基礎：變數、型別、運算子、字串 |
| Week_1 | `20260624_U2.ipynb` | 資料結構：List、Tuple、Dict、Set |
| Week_2 | `20260625_U3.ipynb` | Pandas 資料處理：DataFrame、資料選取、清理、轉換 |
| Week_2 | `20260629_U4.ipynb` | 真實股票資料前處理、曲線圖與 K 線圖繪製 |
| Week_2 | `20260701_U5&U6.ipynb` | SMA / WMA / EMA 均線計算與視覺化 |
| Week_2 | `20260702_U1.ipynb` | 機器學習基礎與工作流程（scikit-learn） |
| Week_3 | `20260713_U2.ipynb` | 金融資料與特徵工程（yfinance） |
| Week_3 | `20260713_U3.ipynb` | 分類模型：Logistic、KNN、SVM、決策樹、Naive Bayes |
| Week_3 | `20260716_U1.ipynb` | 深度學習：神經網路基礎與訓練流程 |
| Week_3 | `20260716_U3.ipynb` | CNN 與股票走勢圖辨識 |
| Week_4 | `20260720_U3.ipynb` | CNN 與股票走勢圖辨識（Colab / GPU 版） |
| Week_4 | `20260721_U4.ipynb` | RNN / LSTM 時序模型 |

### Second_Class

| 主題 | 檔案 | 說明 |
| :--- | :--- | :--- |
| Machine_Learning | `20260723_U1.ipynb` | 機器學習基礎與工作流程（split、訓練、交叉驗證、評估） |

## 技術棧

- **資料處理**：pandas、numpy
- **視覺化**：matplotlib
- **金融資料**：yfinance
- **機器學習**：scikit-learn
- **深度學習**：TensorFlow / Keras（CNN、RNN、LSTM）

## 環境

- Python 3.x
- Jupyter Notebook
- 部分深度學習單元建議於 Google Colab（GPU）執行

## 說明

- `2026/First_Class/`：第一門課的課程 Notebook，依 `Week_N` 週次分類。
- `2026/Second_Class/Machine_Learning/`：第二門課，機器學習相關 Notebook。
- 標示「教師版」的單元含解答與補充註解。

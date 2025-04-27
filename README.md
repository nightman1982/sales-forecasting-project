
# Sales Forecasting Project

## 📅 Opis projektu

Celem projektu jest stworzenie modelu predykcyjnego do prognozowania przyszłej sprzedaży w oparciu o historyczne dane. Projekt obejmuje pełny cykl Data Science: eksplorację danych, inżynierię cech, modelowanie, ewaluację oraz interpretację wyników.

Dane pochodzą z Kaggle i przedstawiają rzeczywiste lub symulowane dane sprzedaży detalicznej.

---

## 🔢 Technologie

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Prophet
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 👀 Struktura katalogów

```plaintext
sales-forecasting-project/
|
├── data/
|    ├── raw/          # dane surowe
|    └── processed/    # dane przetworzone
|
├── notebooks/
|    ├── 01_EDA.ipynb
|    ├── 02_FeatureEngineering.ipynb
|    ├── 03_Modeling.ipynb
|    └── 04_Evaluation.ipynb
|
├── src/
|    ├── data_preprocessing.py
|    ├── feature_engineering.py
|    ├── modeling.py
|    └── evaluation.py
|
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📚 Przebieg pracy

### 1. Eksploracja danych (EDA)
- Wstępna analiza danych
- Identyfikacja sezonowości, trendów i anomalii

### 2. Przygotowanie danych
- Czyszczenie danych
- Tworzenie cech dodatkowych (lagi, rolling means, święta itp.)

### 3. Modelowanie
- Trening bazowych modeli (Linear Regression, Random Forest, XGBoost)
- Eksperymenty z Prophet / LSTM dla zaawansowanej prognozy

### 4. Ewaluacja
- Podział na zbiór treningowy i testowy
- Ocena wyników: RMSE, MAE, MAPE
- Wizualizacja prognoz

### 5. Interpretacja
- Feature Importance
- Porównanie wyników modeli

---

## 🚀 Jak uruchomić projekt

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/twoj-uzytkownik/sales-forecasting-project.git
   ```

2. Przejdź do katalogu projektu:
   ```bash
   cd sales-forecasting-project
   ```

3. Stwórz środowisko i zainstaluj zależności:
   ```bash
   pip install -r requirements.txt
   ```

4. Uruchom notatniki w Jupyterze:
   ```bash
   jupyter notebook
   ```

---

## 📈 Wyniki

- Najlepszy model uzyskał RMSE = `XX.XX`
- Najważniejsze cechy: `feature1`, `feature2`, `feature3`
- Model skutecznie przewiduje sezonowe wzrosty i spadki sprzedaży.

---

## 💬 Kontakt

Jeśli masz pytania lub sugestie, skontaktuj się ze mną:
- Email: [twoj.email@domain.com](mailto:twoj.email@domain.com)
- LinkedIn: [TwojProfil](https://www.linkedin.com/in/twojprofil/)

---

> "Data beats emotions." — Sean Rad


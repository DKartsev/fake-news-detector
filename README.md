# 📰 Fake News Detector (ML-проект)

Проект по машинному обучению, цель которого — построить модель, определяющую, является ли новость фейковой (FAKE) или настоящей (REAL).

## 📌 Цели проекта

- Обработка текстов (TF-IDF)
- Классификация с помощью `PassiveAggressiveClassifier`
- Сравнение разных моделей
- Визуализация метрик
- Достижение точности выше 95%

## 🧠 Используемые технологии

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## 🗃️ Датасет

Датасет с новостями: [Twitter Sentiment Dataset](https://github.com/dD2405/Twitter_Sentiment_Analysis/blob/master/train.csv)

Содержит колонки:
- `text`: текст новости
- `label`: 0 — FAKE, 1 — REAL

## 📈 Результаты

- Финальная модель: `PassiveAggressiveClassifier(C=0.5, class_weight='balanced')`
- Точность: **96.12%**
- Надёжная классификация текстов с визуальной матрицей ошибок

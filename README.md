# RCNN License Plates Recognition

Вступительный экзамен DL Advanced Весна'23 - реализация `CRNN` для решения задачи OCR распознавания автомобильных номеров.


## Структура репозитория

- `./results/` - ipynb, pdf и html версия реализации модели и результатов работы
- `./models/*.pth` - сохраненные PyTorch модели, обученные для решения задачи распознавания автомобильных номеров (CNN + GRU/LSTM)
- `./predictions/*.csv` - предсказания текста автомобильных номеров на тестовом наборе данных в формате `csv`

## Результаты работы модели

| Metric \ Model | CNN + GRU | CNN + Bi-LSTM |
|----------------|-----------|---------------|
| Accuracy       | 0.957     | **0.975**     |
| CER            | 0.007     | **0.004**     |
| Levenshtein    | 0.049     | **0.028**     |

# LCNN Model

Проект содержит реализацию модели **LCNN** для обработки данных и оценки качества на тестовом наборе. На датасете ASVSpoof 2019 
kaggle

---

## Установка

```bash
git clone https://github.com/Mishaq23/lcnn_model.git
cd lcnn_model
pip install -r requirements.txt
```

---

## Использование

Запуск ноутбука:

```bash
jupyter notebook lcnn_model.ipynb
```

Или запуск скрипта (если вынесено в .py):

```bash
python train.py
```

---

## Результаты

- Ошибка на тестовом датасете: **5.6313**

---

## Структура проекта

```
lcnn_model/
│── lcnn_model.ipynb   # Jupyter Notebook с обучением и тестированием
│── requirements.txt   # зависимости
│── README.md          # описание проекта
```

---

## Требования

- Python 3.9+  
- PyTorch / TensorFlow (указать в зависимости от реализации)  
- NumPy, Pandas, Matplotlib

---

## Автор

- [Mishaq23](https://github.com/Mishaq23)

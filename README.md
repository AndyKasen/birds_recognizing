# Классификация птиц по аудиозаписям

Демонстрационный проект по распознаванию видов птиц по их голосам с использованием предобученной модели.

## Описание

Проект использует модель [saadashraf/birds_model](https://huggingface.co/saadashraf/birds_model) с платформы Hugging Face, которая была дообучена для распознавания 264 видов африканских птиц. Модель основана на архитектуре WavLM.

## Функциональность

- Загрузка аудиофайлов форматов WAV, MP3
- Автоматическое определение вида птицы
- Вывод топ-5 наиболее вероятных видов с процентами уверенности
- Визуализация аудиоволны для анализа качества записи

## Быстрый старт

### Вариант 1: Google Colab (рекомендуется)
Нажмите на кнопку ниже для запуска в Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ВАШЕ_ИМЯ/НАЗВАНИЕ_РЕПОЗИТОРИЯ/blob/main/demo_birds.ipynb)

### Вариант 2: Локальный запуск
```bash
git clone https://github.com/ВАШЕ_ИМЯ/НАЗВАНИЕ_РЕПОЗИТОРИЯ.git
cd НАЗВАНИЕ_РЕПОЗИТОРИЯ
pip install -r requirements.txt
jupyter notebook demo_birds.ipynb

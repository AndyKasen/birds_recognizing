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

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AndyKasen/birds_recognazing/blob/main/demo_birds.ipynb)

RAW_link : https://raw.githubusercontent.com/AndyKasen/birds_recognizing/refs/heads/main/demo_birds.ipynb
### Вариант 2: Локальный запуск
```bash
git clone git clone https://github.com/AndyKasen/birds_recognizing.git
cd birds_recognizing.git
pip install -r requirements.txt
jupyter notebook demo_birds.ipynb

### Где можно найти аудиозаписи птиц:
https://xeno-canto.org. Не забудьте скачать файл с ресурса.

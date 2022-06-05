# Recnizer

> [![](https://img.shields.io/badge/193-Иван%20Добросовестнов-orange)](https://t.me/ivankot13 'telegram')
> [![](https://img.shields.io/badge/193-Степан%20Денисов-blue)](https://t.me/sd_denisoff 'telegram')

## Описание

Система распознавания информации с кассовых чеков

## Стек технологий

#### Deep Learning

- pytorch

#### Анализ данных

- numpy, pandas
- scikit-learn

#### Данные
Размеченные данные чеков доступны по [ссылке]([url](https://drive.google.com/drive/folders/1CtVM738iChh35Izptv0svmsgiGNq47ad?usp=sharing)).

## Инструкция по запуску

1. Установите [python3](https://www.python.org/)

2. Склонируйте репозиторий и перейдите в директорию с проектом
   ```bash
   $ git clone https://github.com/sd-denisoff/recnizer.git && cd recnizer
   ```

3. Создайте и активируйте виртуальное окружение
   ```bash
   $ virtualenv --python=python3.9 venv
   $ source venv/bin/activate
   ```

4. Установите зависимости
   ```bash
   $ pip3 install -r requirements.txt
   ```

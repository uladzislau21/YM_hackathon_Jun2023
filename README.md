# Яндекс Хакатон: [Маркет х Практикум] Июнь 2023
**Задача хакатона:** Создать алгоритм сервиса и интерфейс упаковщика для Яндекс Маркета.

**Задача команды DS:** С высокой точностью рекомндовать правильную упаковку для заказа, которая позволит доставить товары без порчи клиенту и 
минимизирует затраты на упаковочный материал

# Содержание репозитория:

## 1. [Блокнот с исследовательским анализом данных](https://github.com/uladzislau21/YM_hackathon_Jun2023/blob/main/yandex_hackathon_eda_by_ds_team_4.ipynb)
Проведенн EDA.

## 2. [Блокнот с предобработкой данных](https://github.com/uladzislau21/YM_hackathon_Jun2023/blob/main/yandex_hackathon_preproseccing_by_ds_team_4.ipynb)
В данной работе проведена предобработка данных с учетом особенностей выявленных при исследовательском анализе

## 3. [Блокнот с моделингом](https://github.com/uladzislau21/YM_hackathon_Jun2023/blob/main/yandex_hackathon_modelling_by_ds_team_4.ipynb)
В моделинге были выбраны наилучшие для задачи модели и параметры к ним, а так же отброшены признаки, снижающие качество. Для достижения высокого результат были выбраны две 
модели:

1. Модель кластеризации (Kmeans) на основе линейных размеров и карготипов товаров
2. Модель FAISS для нахождения нескольких подходящих вариантов упаковок. Несколько вариантов упаковок позволят иметь в запасе свободу выбора. Например, в случае отсутствия 
однйо из упаковок на складе.

## 4. [Блокнот с заключительными выводами и анализом бизнес метрики](https://github.com/uladzislau21/YM_hackathon_Jun2023/blob/main/yandex_hackathon_result_by_ds_team_4.ipynb)
Сравнительный анализ итоговых результатов и их значение для бизнеса.

## 5. [Директория с файлами для Docker образа](https://github.com/uladzislau21/YM_hackathon_Jun2023/tree/main/for_docker_images)
Дирректория содержит в себе готовое backend приложение с моделями и  полностью рабочую инструкцию сборки Docker образа для последующего внедрения в общий сервис.

## 6. [Скрипт предобработки и моделинга](https://github.com/uladzislau21/YM_hackathon_Jun2023/blob/main/preprocessing_data_and_train_model.py)
Скрипт предназачен для полной предобработки данных, обучения и выгрузки масштабизаторов, векторизатора и моделей.

P.S. Работает долго.

## 7. [Диреткория для исходных данных](https://github.com/uladzislau21/YM_hackathon_Jun2023/tree/main/initial_data)
В дирректорию помещаются исходные данные для хакатона.

# Итоги работы
В результате проведенной работы разработан алгоритм, который позволяет группировать товары с выбором упаковки для каждой группы. Группировка товаров позволяет экономить место 
при транспортировке и значительно снизить затраты на упаковочный материал.

# Состав команды:

- [Ярослав Князев](https://github.com/Yaroslav-Kn)
- [Владислав Вододохов](https://github.com/uladzislau21)
- [Станислав Мокров](https://github.com/GreyGreyWolf)

Описание проекта

Проект направлен на прогнозирование вероятностей перехода клиента в каждый продуктовый кластер. Модель использует алгоритм CatBoostClassifier. Взвешенная метрика ROC AUC используется для оценки точности прогнозирования.

Требования

Для запуска проекта необходим Python 3.6 или выше и библиотеки:
numpy
pandas
catboost
scikit-learn
openpyxl
matplotlib

Установить необходимые библиотеки можно с помощью команды
pip install numpy pandas catboost scikit-learn openpyxl matplotlib

Данные

train_data.pqt: файл Parquet, содержащий обучающие данные.
test_data.pqt: файл Parquet, содержащий тестовые данные.
cluster_weights.xlsx: файл Excel, содержащий веса кластеров.
sample_submission.csv: CSV файл, используемый в качестве шаблона для отправки результатов.

Запуск

Для запуска проекта выполните следующие шаги:

1. Убедитесь, что все необходимые библиотеки установлены.
2. Разместите файлы данных (train_data.pqt, test_data.pqt, cluster_weights.xlsx, sample_submission.csv) в рабочей директории.
3. Запустите скрипт Python: python script.py
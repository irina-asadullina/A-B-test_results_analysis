# A/B–тестирование новой механики оплаты на сайте

**Цель:** проанализировать две группы пользователей, принявших участие в эксперименте, принять решение о выкачке новой механики оплаты на основе статистических критериев  
**Стэк:** Pandas, Seaborn, Matplotlib, Numpy, API, bootstrap, критерий хи-квадрат

**Этапы работы:**
1) Сбор, предобработка и эксплоративный анализ данных
2) Выбор метрик для анализа результатов эксперимента
3) Проведение статистических тестов
4) Интерпретация результатов и принятие решения на их основе

**Результаты:**
1) Прописан запрос к API Яндекс.Диску для доступа к csv-файлам с данными
2) Выбраны метрики для анализа, сформулированы по три нулевых и альтернативных гипотезы
3) Применен критерий хи-квадрат и написана функция для проведения bootstrap-анализа
4) По результатам тестов принято решение, что выкатывать новую механику оплаты на сайте нецелесообразно, а также замечена необходимость проверки системы сплитования в данном эксперименте
5) Написаны функции, обогащающие данные, пересчитывающие метрики и строящие графики по получаемым метрикам

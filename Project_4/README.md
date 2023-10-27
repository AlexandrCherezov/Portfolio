# Приоритизация гипотез, проведение A/B-теста и анализ его результатов в  крупном интернет-магазине. 

В наше распоряжение предоставлены 9 гипотез для увеличения выручки интернет-магазина, подготовленных вместе с отделом маркетинга. 

# В результате исследования сформированы выводы:
- продажи в группе В выглядят лучше 
- следует принять решение остановить тест ввиду наличия постоянного и ежедневного улучшения кумулятивной выручки в тестируемой группе по сравнению с контрольной группой.
- Возможно, что на такие результаты теста повлияли следующие не совсем корректные исходные данные :
 - Количество клиентов разных групп, посещающих сайт, различается более, чем на 10% в течение 6 дней из 31 дня сбора данных. Это существенная разница 
 - Один и тот же клиент мог присутствовать как в группе А, так и в группе В, что является нежелательным и может повлиять на результаты теста
 - Отсутствует возможность рассчитать время, проходящее между посещением клиентом сайта и совершением клиентом покупки и соотнести полученные данные с периодом исследования.


# Рекомендации для отдела маркетинга. При проведении последующих тестов для получения корректных результатов учесть рекомендации:

-  иметь возможность рассчитать время, проходящее между посещением клиентом сайта и совершением клиентом покупки и соотнести полученные данные с периодом исследования.
-  производить разделение клиентов между группами с разницей не более, чем 1%
-  не допускать, чтобы один и тот же клиент мог присутствовать как в группе А, так и в группе В

Также следует обратить внимание и подвергуть дополнительному анализу то, что среднее количество заказов на покупателя в группе А больше во всем периоде тестирования, чем среднее количество заказов на покупателя в группе В (пункт 6.10) - интренет магазин мог бы еще увеличить конверсию в группе В.

# В исследовании мы рассмотрели и приоритизировали гипотезы:
- Применили фреймворки ICE  и RICE для приоритизации гипотез. 
- Выяснили, как изменилась приоритизация гипотез при применении RICE вместо ICE и почему так произошло.

# После чего запустили A/B-тест и проанализировали его результаты:
- Рассчитали значения и построили графики 
 - кумулятивной выручки по «сырым» и "очищенным" данным.
 - кумулятивного среднего чека и кумулятивного среднего количества заказов на посетителя 
 - определили границу для определения аномальных пользователей и аномальных заказов
 - рассчитали статистическую значимость различий в среднем количестве заказов на посетителя и в среднем чеке заказа между группами по «сырым» и "очищенным" данным.

# В качестве составной части А/В теста мы сформулировали и проверили гипотезы:
- о наличии различий в среднем количестве заказов на посетителя между группами по «сырым»  и «очищенным» данным
- о наличии различий в среднем чеке заказа между группами по «сырым» и «очищенным» данным

# Ход исследования:
- Загрузка данных из предоставленного файла со списком гипотез
- Изучение данных
- Приотеризация гипотез
- Загрузка данных из предоставленных файлов с данными проведенных A/B-тестов и подготовка их к анализу
- Изучение общей информации о каждом датафрейме
- Предобработка данных
- Исследовательский анализ данных
- Анализ А/В теста и проверка гипотез
- Выводы и заключения


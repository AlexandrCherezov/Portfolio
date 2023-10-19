# Исследование поведения пользователей мобильного приложения стартапа, продающего продукты питания. Событийная аналитика.
В наше распоряжение предоставлены данные о действиях пользователей мобильного приложения при проведении A/A/B-эксперимента.  
Рассмотрим, как ведут себя пользователи мобильного приложения. 
Изучим воронку продаж. Узнаем, как и сколько пользователей доходят до покупкиБ а соклько - не доходят.

# В результате исследования сформированы выводы:
- отсутствует возможность подтвердить статистически значимое различие в событиях при заданном уровне статистической значимости 0.05. То есть исследование не может подтвердить, что замена шрифта повлияла на частоту совершаемых пользователями событий.
- Возможно, что на такие результаты теста повлияли следующие не совсем корректные исходные данные :
  - Рассчитанное и запланированное время тести составило 13 дней. Фактически тест проводился только 7 дней 

## **В исследовании:**
- Изучена воронка продаж и воронка событий. Узнали, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах и на каких именно шагах
- Исследовали результаты A/A/B-эксперимента, в котором исследуется поведение пользователей при изменении шрифтов во всём приложении. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. 
- При сравнении значений A и A тестов проверили наличие искажения результатов и факторы, которые к ним привели.
- Выявили и проанализировали воронку продаж

## **Запустили A/B-тест и проанализировали его результаты:** 
- проверили наличие статистически значимого различия между группами
- выяснили, представлены ли тмеющиеся у нас данные в виде нормального распредления
- выяснили наличие и избавились от аномальных значений
- провели статистические тесты между представленными группами

## **В качестве составной части А/В теста сформулировали и проверили гипотезы**:
- об отсутствии статистически значимого различия данных между двумя контрольными группами
- о наличии статистически значимого различия между каждой из контрольных групп и экспериментальной группой
- о наличии статистически значимого различия между объединенной контрольной группой и экспериментальной группой 

## **Ход исследования:**
- Загрузка данных из предоставленных файлов с данными проведенных А/A/B-тестов и подготовка их к анализу
- Изучение общей информации о датафрейме и предобработка данных
- Исследовательский анализ данных
- Изучение воронки событий
- Анализ данных А/А/В теста 
- Проверка гипотез
- Выводы и заключения

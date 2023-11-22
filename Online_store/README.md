# Приоритизация гипотез, проведение A/B-теста и анализ его результатов в интернет-магазине.

## Данные
Заказчик предоставил информацию:
### список гипотез:
- краткое описание гипотезы	
- охват пользователей по 10-балльной шкале	
- влияние на пользователей по 10-балльной шкале	
- уверенность в гипотезе по 10-балльной шкале	
- затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы	
### данные о заказах:
- идентификатор заказа	
- идентификатор пользователя, совершившего заказ	
- дата, когда был совершён заказ	
- выручка заказа	
- группа A/B-теста, в которую попал заказ
### данные о пользователях:
- дата	
- группа A/B-теста	
- количество пользователей в указанную дату в указанной группе A/B-теста	

## Задача 
- приоритизировать предоставленные гипотезы
- проанализировать результаты A/B-теста
- построить графики:
 - кумулятивной выручки по «сырым» и "очищенным" данным.
 - кумулятивного среднего чека и кумулятивного среднего количества заказов на посетителя 
- определить границу для определения аномальных пользователей и аномальных заказов
- рассчитать статистическую значимость различий в среднем количестве заказов на посетителя и в среднем чеке заказа между группами по «сырым» и "очищенным" данным.
- сформулировать и проверить гипотезы

## Используемые библиотеки
- **pandas**  
- **IPython.display**
- **matplotlib**
- **numpy**
- **datetime**
- **scipy**
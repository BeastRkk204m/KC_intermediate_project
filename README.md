# KC_cohort_RFM_e_comm_report

Структура проекта:
1. Project.ipynb - файл отчёта в Jupiter Notebook.
2. RF.PNG - приложение к отчёту
3. Readme

Описание проекта:\
Проведён предварительный анализ данных e-commerce. Выведена основная информация о пользователях, покупках, выручке.\
Проведён когортный анализ с выявлением когорты с самым высоким Retantion на третий месяц.\
Построена RFM-сегментация, выявлены наиболее важные сегменты пользователей.\

Выводы по результатам анализа:
1. На данный момент наша основная аудитория, которая приносит наибольший доход - люди, которые совершают 1 покупку, покупая на сумму до 839 долларов, при этом такие клиенты - это практически абсолютное большинство.
2. Retention Rate нашего магазина очень низок. Для увеличения дохода можно попробовать увеличить Retention именно этой аудитории - кластеры *66, *65, *64 - повлияв на неё рекламой или акциями. Возможно также, что дело в качестве товара, и люди не хотят возвращатся за новой покупкой.
3. У нас есть клиенты - например, по кластерам 111, 131, 321 - совершившие от 3 до 12 покупок на стоимость выше 2,5 тысяч до 13,3 тысяч долларов, тоесть закупающиеся большими партиями,но они немногочисленны. Возможно, стоит рассмотреть стратегии по привлечению именно таких клиентов.
4. По разбиению на сегменты можно сказать следующее:\
1) лояльных и проявивших лояльность клиентов очень мало, почти 0% от общего количества, но они есть\
2) чтобы повысить Retention, в первую очередь нужно обращать внимание на красные и на жёлтые сегменты на графике сегментов, эти пользователи наиболее расположены к повторным покупкам в нашем магазине.
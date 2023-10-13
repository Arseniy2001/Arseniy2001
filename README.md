# Arseniy2001
### О себе:
<ul>
<li>Уверенно пишу код на Python
<li>Знаю библиотеками Pandas, NumPy, Matplotlib, Seaborn 
<li>Умею проводить А/В тесты
<li>Пишу сложные SQL запросы
<li>Умею работать в BI системах
<li>Автоматизирую процессы через Airflow
<li>Владею математической базой 
</ul>



### Проектная деятельность онлайн курса «Симулятор аналитика»:

[Провел A/A тест](https://github.com/Arseniy2001/23/blob/master/main%C2%A0—%20копия.c) по метрике CTR с помощью t-testа, извлекая 10000 раз подборки по 500 пользователей 
[Провел A/B тесты](https://github.com/Arseniy2001/Analyst_simulator/blob/main/AB_1.ipynb), используя различные методы: t-test, тест Манна Уитни, t-test со сглаженным CTR, Пуассоновский бутстреп, t-test поверх букетного преобразования 
[A/B тест](https://github.com/Arseniy2001/Analyst_simulator/blob/main/AB_2.ipynb)    по метрике линеаризованных лайков от Яндекса для отношений вида  x/y 

Прогнозирование метрик. 
[Оценил эффективность флешмоба]https://github.com/Arseniy2001/Analyst_simulator/blob/main/MP_1.ipynb), который проводился в приложении, с помощью библиотеки CausalImpact. (
Спрогнозировал активность пользователей в ближайший месяц с помощью библиотеки orbit (https://github.com/Arseniy2001/Analyst_simulator/blob/main/MP_2.ipynb)

Построение ETL-Пайплайна в Airflow.  
Написал DAG которой выгружает данные приложения из clickhouse, преобразовывает их и отправляет в новую таблицу clickhouse. (https://github.com/Arseniy2001/Analyst_simulator/blob/main/Senya_dag1.py) 
Автоматизировал отчетность, с помощью ETL-Пайплайна. DAG  каждый день  отправлял основные данные по ленте приложения за вчерашний день в телеграм канал, используя Бот из телеграмма. (https://github.com/Arseniy2001/Analyst_simulator/blob/main/Senya_raport_1.py)
DAG по всему приложению за вчерашний день в телеграм канал (https://github.com/Arseniy2001/Analyst_simulator/blob/main/Senya_raport_2.py)
Написал систему алертов для приложения. В случае аномального отклонения метрик, в чат телеграмма приходило оповещение. DAG срабатывал каждые 15 минут. (https://github.com/Arseniy2001/Analyst_simulator/blob/main/Senya_alert.py)





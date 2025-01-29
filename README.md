Тестовое задание 

Задача: реализовать на ASP .NET CORE 6 Web API, REST-сервис по обмену валют используя Swagger. 
•	В рамках задания сервис не использует аутентификацию и авторизацию;
•	В разрабатываемой системе можно создать неограниченное кол-во пользователей. Добавление пользователя производится через REST-API;
•	У каждого пользователя есть денежный счет на каждую валюту в системе;
•	Через REST-API можно изменять баланс указанного пользователя;
•	В системе можно создать неограниченное количество валют. Добавление валют производится через REST-API.  

Система обмена должна конвертировать сумму из первой валюты во вторую валюту по заданному курсу. Курс обмена всегда положительное число не равное нулю, является входным параметром. При конвертации со счета пользователя списывается введенная им сумма в первой валюте и зачисляется рассчитанная сумма во второй валюте с вычетом комиссии.  Комиссия рассчитывается как сумма полученной суммы во второй валюте умноженное на процент комиссии. Процент комиссии является входным параметром (по умолчанию равен 0,05%). Вызов функции обмена производится через REST-API.

Ваша задача: написать вышеуказанный сервис с следующими условиями: входные значения обязательно должны проходить валидацию на корректные значении в случае ошибки сообщать об этом в сообщении. 
# ExchangeCurrency
тз по обмену валют

# Plancer
## Описание
Plancer - это удобный менеджер задач, который поможет вам визуализировать свои планы и сконцентиророваться на их выполнении. Широкий функционал поможет вам создавать задачи, а также подбирать для себя те, к которым вы хотели бы приступить. Ваша активность сохраняется и в любой момент вы сможете просмотреть свою статистику и похвастаться ею!
## Функции
- Регистрация и аутентификация пользователя
- Присвоение задачам разных параметров, таких как приоритет, срок и прогресс выполнения
- Сортировка задач
- Создание тематических групп задач
- Режим работы
- Вывод статистики пользователя
## Сущности
### User
|Field Name | Type  
|-----------|:-----------:|
| id | integer|
|username| varchar|
|email|varchar|
|password|varchar|
|creation_date|date|

### Task 
|Field Name | Type  
|-----------|:-----------:|
| id | integer|
|name| varchar|
|status|varchar|
|priority|integer|
|deadline|date|
|time_spent|time|
|task_group_id|integer|

### Task_Group 
|Field Name | Type  
|-----------|:-----------:|
| id | integer|
|name| varchar|
|user_id|integer|


## Главная страница
![image](https://github.com/CaptainAlekor/ITiROD/assets/79224183/fe4cb888-180f-48ad-8de3-8b1f7828cbc7)
## Страница регистрации
![image](https://github.com/CaptainAlekor/ITiROD/assets/79224183/e16cd67f-ed3b-479d-9dc2-f4afb6e854e5)
## Статистика пользователя
![image](https://github.com/CaptainAlekor/ITiROD/assets/79224183/d1ed82f1-1c76-4708-96b3-483ade787755)



https://www.figma.com/file/6mRYCjjAfXxkqfkmiWWRNp/Untitled?node-id=11%3A53&t=0oCCW5VPmOaMYcak-1

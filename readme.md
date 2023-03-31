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
![изображение](https://user-images.githubusercontent.com/79224183/229195001-8a6b2d32-64d4-49cf-a980-0e7748f516f8.png)
## Страница регистрации
![изображение](https://user-images.githubusercontent.com/79224183/229195144-696b1f97-14bf-41b8-816d-c7ba5dd3b177.png)
## Статистика пользователя
![изображение](https://user-images.githubusercontent.com/79224183/229195270-499f4b1a-7b87-4967-b401-a71f3fe206a5.png)


https://www.figma.com/file/6mRYCjjAfXxkqfkmiWWRNp/Untitled?node-id=11%3A53&t=0oCCW5VPmOaMYcak-1

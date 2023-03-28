# TickTack

## Описание:
TickTack - это менеджер задач, который позволяет людям быть более продуктивными. Он может быть полезен студентам, учащимся, а также всем людям которые хотят улучшить свою самоорганизацию, дисциплину, помогает организовать аспекты своей жизни. Приложение позволяет анализировать результат своей работы благодаря выводимой статистике за неделю.

## Функции:
1. Раздел избранных задач
2. Регистрация и аутенфикация пользователя
3. Фильтрация задач по заданным параметрам
4. Задание приоритета задачи
5. Разбиение задач на группы
6. Показ статистики выполненных задач за неделю

## Модели данных:

### TaskGroup
|Field Name | Type  
|-----------|:-----------:|
| Id | PK |
| Name | VARCHAR(64) |


### Task
|Field Name | Type  
|-----------|:-----------:|
| Id | PK |
| Name | VARCHAR(64) |
| Description | VARCHAR(255) |
| Priority | Integer |
| isFavorite | Integer |
| isCompleted | Integer |
| taskGroupId | FK |

### User
|Field Name | Type  
|-----------|:-----------:|
| Id | PK |
| Username | VARCHAR(64) |
| Password | VARCHAR(64) |
| Email | VARCHAR(64) |

## Главная страница сайта
![Главная страница сайта](./Lab2/mainPage.jpg "Главная страница сайта")

## Страница регистрации
![Страница регистрации](./Lab2/signUp.jpg "Страница регистрации")

## Страница входа в аккаунт
![Страница входа в аккаунт](./Lab2/signIn.jpg "Страница входа в аккаунт")

## Страница анализа недельной активности
![Страница анализа недельной активности](./Lab2/weekSummary.jpg  "Страница анализа недельной активности")

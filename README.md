# course_work_5_release

___
## Курсовой проект по Работе с базами данных 

___
## Задачи
### Закрепить первоначальные знания по темам:
1. Создание БД;
2. Создание таблиц;
3. Базовые SQL-запросы;
4. Продвинутый синтаксис;
5. Data Definition Language;

___
## Установка

1. Откройте проект с помощью Get from VCS.
2. Введите ссылку на удалённый репозиторий. 
    ```
    git@github.com:AndrewDyakonow/Course_work_5.git
   ```
3. Создайте и активируйте виртуальное окружение.
    ```
    python3 -m venv venv
    source venv/bin/activate
   ```
4. Установите зависимости.
    ```
    pip install -r requirements.txt
   ```
___

## Описание

1. При запуске файла main.py необходимо набрать ключевое слово или фразу для поиска и нажать ENTER
2. Если по ключевому слову или фразе вакансий не будет найдено, то выведется соответствующее сообщение
3. После получения вакансий, их можно отсортировать по зарплате, от большей к меньшей
4. Далее автоматически создастся и заполнится база данных по найденным вакансиям
5. В завершении можно выбрать запрос из базы данных для удобного отображения вакансий
6. Обратите внимание, что для запроса № 5 необходимо будет ввести ключевое слово для поиска по названию вакансии
7. В конце необходимо набрать "0", для завершения работы

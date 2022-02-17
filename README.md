# JSON

4. Создать внешний репозиторий c названием JSON

    `https://github.com/npetyaeva/JSON.git`

5. Клонировать репозиторий JSON на локальный компьютер

    `git clone https://github.com/npetyaeva/JSON.git` 
    
    `cd JSON`

6. Внутри локального JSON создать файл “new.json”

    `touch new.json`

7. Добавить файл под гит.

    `git add new.json`

8. Закоммитить файл.

    `git commit -m "Added new.json"`

9. Отправить файл на внешний GitHub репозиторий.
    
   `git push`
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

       `vim new.json`
       ```
       { 
         "name": Петяева Наталья,
         "age": 43,
         "pets": 3,
         "salary": 1000
       }
       ```
11. Отправить изменения на внешний репозиторий.

       `git commit -am "Modified new.json"`
       
       `git push`
12. Создать файл preferences.json.

       `touch preferences.json`
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

       `vim preferences.json`
       ```
       { 
          "favorite movie": "Flashbacks of a Fool",
          "favorite series": "Altered Carbon",
          "favorite food": "стейк",
          "favorite season": "осень",
          "country": "Япония"
       }
       ```
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.

    `touch sklls.json`

    `vim sklls.json`
    ```
    { 
      "6": "Что такое JSON, XML. Их структура.",
      "7": "Тестирование API.",
      "8": "Снятие и чтение логов.",
      "9": "Postman, Fidler.",
      "11": "Dev Tools веб браузеров (Google Chrome, FireFox)."
    }
    ```
15. Отправить сразу 2 файла на внешний репозиторий.

    `git add .`

    `git commit -m "Added preferences.json & sklls.json"`

    `git push`
16. На веб интерфейсе создать файл bug_report.json.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

    ```
    {
      "ID": "BR000",
      "Summary": "Заголовок",
      "Description": [
                      "1. ...",
                      "2. ..."
                      ],
      "Actual result": "Фактический результат",
      "Еxpected result": "Ожидаемый результат",
      "Enviroment":
      {
              "OS": "ОС",
              "Browser": "Браузер"
      },
      "Severity": "Серьезность",
      "Priority": "Приоритет",
      "Author": "Автор",
      "Sign to": "Назначено на",
      "Attachments": "Вложения"
    }
    ```
20. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

       `https://github.com/npetyaeva/JSON/blob/main/bug_report.json`
   
20. Синхронизировать внешний и локальный репозиторий JSON

    `git pull`

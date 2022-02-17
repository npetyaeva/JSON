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
       ```json
       { 
         "name": "Natalia Petyaeva",
         "age": 43,
         "pets": 3,
         "salary": 1000
       }
       ```
11. Отправить изменения на внешний репозиторий. Использую команду `commit` с двумя параметрами: `-а` - проиндексирует отслеживаемые файлы (замена `git add`) и `-m` - написание комментария через командную строку:

       `git commit -am "Modified new.json"`
       
       `git push`
12. Создать файл preferences.json.

       `touch preferences.json`
       
       `git add preferences.json`
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

       `vim preferences.json`
       
       ```json
       { 
          "favorite movie": "Flashbacks of a Fool",
          "favorite series": "Altered Carbon",
          "favorite food": "steak",
          "favorite season": "autumn",
          "country": "Japan"
       }
       ```
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.

    `touch sklls.json`
    
    `git add skills.json`

    `vim sklls.json`
    ```json
    { 
      "item06": "What is JSON, XML. Their structure.",
      "item07": "API testing.",
      "item08": "How to view read logs.",
      "item09": "Postman, Fidler.",
      "item11": "Dev Tools of web browsers (Google Chrome, FireFox)."
    }
    ```
15. Отправить сразу 2 файла на внешний репозиторий.

    `git commit -am "Added preferences.json & sklls.json"`

     `git push`
16. На веб интерфейсе создать файл bug_report.json.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

    ```json
    {
      "ID": "0001",
      "Summary": "Missing product images on the Product page ",
      "Priority": "High",
      "Severity": "Major",
      "Еxpected result": "Product images are displayed on the Product page",
      "Actual result": "All product images are missing",
      "Steps": 
      [
              "1. Open www.storeName.com",
              "2. Find and select a product on the Main page and make sure that the Product page has loaded"                     
      ],
      "Enviroment":
      {
              "OS": "Windows 10",
              "Browser": "Google Chrome 98.0.4758.102, (x86_64)"
      },
      "Attachments": 
      {
              "link1": "https://...",
              "link2": "https://..."
      }
    }
    ```
20. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

       `https://github.com/npetyaeva/JSON/blob/main/bug_report.json`
   
20. Синхронизировать внешний и локальный репозиторий JSON

    `git pull`

# **🗲JSON🗲**

*Задание 1. Создать внешний репозиторий c названием JSON.*

`Решение`⮯ 

1. Перейти по ссылке
2. Нажать "New"
3. Ввести "JSON" в поле "Repository name"
4. Выбрать "Public" и "Add a README file"
5. Нажать "Create repository"
---

*Задание 2. Клонировать репозиторий JSON на локальный компьютер.*

`Решение`⮯ 

Нажать "Code"
Выбрать "SSH"
Нажать "Скопировать ссылку на репозиторий"
В GitBash зайти в папку (в которой будет размещен репозиторий)
Клонировать репозиторий на локальный компьютер:
git clone "git@github.com:VitasQA/JSON.git"
Войти в папку "Json":
cd Json 
---

*Задание 3. Внутри локального "JSON" создать файл “new.json”.*

`Решение`⮯ 

Создать файл:
touch new.json
Посмотреть состояние файлов в рабочем каталоге и индексе:
git status
---

*Задание 4. Добавить файл под гит.*

`Решение`⮯ 

git add new.json
Посмотреть состояние файлов в рабочем каталоге и индексе:
git status
---

*Задание 5. Закоммитить файл.*

`Решение`⮯ 

Сделать снимок текущего состояния изменений, добавленных в раздел проиндексированных файлов:
git commit -m "add new.json"
---

*Задание 6. Отправить файл на внешний GitHub репозиторий.*

`Решение`⮯ 

Выгрузить содержимое локального репозитория в удаленный:
git push
---

*Задание 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.*

`Решение`⮯ 

Открыть текстовый редактор Vim:
vim new.json
Нажать " i "
Ввести информацию:
{
	"full_name": "Kruglik_Vitaliy_Iv",
	"age": 32,
	"pets_number": 0,
	"future_salary": 1500
}

Нажать "Esc"
Нажать ":wq"
---

*Задание 8. Отправить изменения на внешний репозиторий.*

`Решение`⮯ 

git add new.json
git commit -m "modified file"
git push
---

*Задание 9. Создать файл preferences.json.*

`Решение`⮯ 

cat > preferences.json
---

*Задание 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм,сериал, еда, время года, страна которую хотели бы посетить) в формате JSON.*

`Решение`⮯ 

Ввести информацию:
{
  "favorite_film": "Terminator",
  "favorite_series": "The Last Of Us",
  "favorite_food": "Pasta",
  "favorite_season": "Winter",
  "favorite_country": "Italia"
}

Нажать "Enter"
Нажать "Ctrl + D"
---

*Задание 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.*

`Решение`⮯ 

Ввести:
cat > skills.json
Ввести информацию:
{
 "skills": [
  "Mobile testing",
  "Postman",
  "software testing theory",
  "client-server arhitecture",
  "API testing",
  "Android Studio"
 ]
}

Нажать "Enter"
Нажать "Ctrl + D"
---

*Задание 12. Отправить сразу 2 файла на внешний репозиторий.*

`Решение`⮯ 

git add .

git commit -m "modified_file"

git push
---

*Задание 13. На веб интерфейсе создать файл bug_report.json.*

`Решение`⮯ 

Зайти в репозиторий "JSON"
Нажать кнопку "Add file"
Нажать кнопку "Create new file"
В поле "Name your file" ввести "bug_report.json"
---

*Задание 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*

`Решение`⮯ 

Нажать кнопку "Commit new file"
---

*Задание 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.*

`Решение`⮯ 

Открыть файл "bug_report.json"
Нажать кнопку "Редактировать"
Ввести информацию:
{
"BugReport":[
   {
   "summary": "The login page crashes when attempting to enter a username with a special character",
   "descriprion": "WS dosen't provide information if response containes more than 9 characters",
   "actualResult": "information gets",
   "expectedResult": "information doesen't get",
   "requirementId": "requirement",
   "reproducedOn": "Win 11",
   "reproducibility": "always",
   "workaround": "no",
   "stepsTOreproduce":[
        {"one": "1. Navigate to the login page",
        "two": "2. Enter a username with a special character (e.g. !@#$%)",
        "three": "3. Click on the 'Login' button",
        "four": "4. Observe the page crashing",
    }
                      ],
   "severity": "minor",
   "priority": "low"
   }  
   ]
}
---

*Задание 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*

`Решение`⮯ 

Нажать кнопку "Commit changes"
---

*Задание 17. Синхронизировать внешний и локальный репозиторий JSON.*

`Решение`⮯ 

```bash
git pull
```

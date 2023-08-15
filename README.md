# <a id='back_to_list'>JSON</a>

### <a id='back_to_list_p_1'>JSON </a>

| №  | Title EN | Answer |
|----|----------|--------|
| <a id='back_task_1_part_1'>1</a>  | [Create an external repository named JSON.](#task_1_part_1) <details><summary>RU</summary>1 Создать внешний репозиторий c названием JSON.</details> |  |
| <a id='back_task_2_part_1'>2</a>  | [Clone JSON repository to local machine.](#task_2_part_1) <details><summary>RU</summary>2 Клонировать репозиторий JSON на локальный компьютер.</details> | git clone https://github.com/MaksimVolkov/json.git <br />cd json/ <br />ls -la |
| <a id='back_task_3_part_1'>3</a>  | [Inside the local JSON, create the file "new.json".](#task_3_part_1) <details><summary>RU</summary>3 Внутри локального JSON создать файл "new.json".</details> | touch new.json <br />ls <br /> |
| <a id='back_task_4_part_1'>4</a>  | [Add file under git.](#task_4_part_1) <details><summary>RU</summary>4 Добавить файл под гит.</details> | git add . <br />or <br />git add new.json |
| <a id='back_task_5_part_1'>5</a>  | [Commit file.](#task_5_part_1) <details><summary>RU</summary>5 Закоммитить файл.</details> | git commit -m "add new.json" |
| <a id='back_task_6_part_1'>6</a>  | [Push file to external GitHub repository.](#task_6_part_1) <details><summary>RU</summary>6 Отправить файл на внешний GitHub репозиторий.</details> | git push |
| <a id='back_task_7_part_1'>7</a>  | [Edit the contents of the "new.json" file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.](#task_7_part_1) <details><summary>RU</summary>7 Отредактировать содержание файла "new.json" - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.</details> | vim new.json <br /> INSERT <br />{ <br />  "user": { <br />    "id":1, <br />    "name":"Dobby", <br />    "last_name":"Houseelf", <br />    "full_name": "Dobby Houseelf Potterovich", <br />    "age": 30, <br />    "number_of_pets": 1, <br />    "desired_salary": 75000 <br />  }} <br />:wq <br />ENTER <br /> |
| <a id='back_task_8_part_1'>8</a>  | [Submit changes to external repository.](#task_8_part_1) <details><summary>RU</summary>8 Отправить изменения на внешний репозиторий.</details> | git add . <br />git commit -m "added content to file new.json" <br />git push <br /> |
| <a id='back_task_9_part_1'>9</a>  | [Create preferences.json file](#task_9_part_1) <details><summary>RU</summary>9 Создать файл preferences.json</details> | touch preferences.json |
| <a id='back_task_10_part_1'>10</a>  | [In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.](#task_10_part_1) <details><summary>RU</summary>10 В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.</details> | vim preferences.json <br />INSERT <br />{ <br />  "preferences": { <br />    "favorite_movie": "Terminator 2", <br />    "favorite_tv_show": "The Big Bang Theory", <br />    "favorite_food": "Nepalese", <br />    "favorite_season": "Summer", <br />    "desired_travel_destination": "United Kingdom" <br />  } <br />} <br />CTRL+C <br />:wq <br />ENTER |
| <a id='back_task_11_part_1'>11</a>  | [Create a sklls.json file to add information about the skills that will be studied in the course in JSON format](#task_11_part_1) <details><summary>RU</summary>11 Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON</details> | touch skills.json <br />vim skills.json <br />INSERT <br />{ <br />  "ru": [ <br />    { <br />      "title": "Основы работы ...", <br />      "sections": [{...},{...}] <br />    } <br />  ], <br />  ... see full version in Description.. <br />} <br />CTRL+C <br />:wq <br />ENTER |
| <a id='back_task_12_part_1'>12</a>  | [Upload 2 files at once to an external repository.](#task_12_part_1) <details><summary>RU</summary>12 Отправить сразу 2 файла на внешний репозиторий.</details> | git add . <br />git commit -m "commit multiple files" <br />git push |
| <a id='back_task_13_part_1'>13</a>  | [Create a bug_report.json file on the web interface.](#task_13_part_1) <details><summary>RU</summary>13 На веб интерфейсе создать файл bug_report.json.</details> | See in Description |
| <a id='back_task_14_part_1'>14</a>  | [Make Commit changes (save) changes on the web interface.](#task_14_part_1) <details><summary>RU</summary>14 Сделать Commit changes (сохранить) изменения на веб интерфейсе.</details> | See in Description |
| <a id='back_task_15_part_1'>15</a>  | [On the web interface, modify the bug_report.json file, add a bug report in JSON format.](#task_15_part_1) <details><summary>RU</summary>15 На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.</details> | See in Description |
| <a id='back_task_16_part_1'>16</a>  | [Make Commit changes (save) changes on the web interface.](#task_16_part_1) <details><summary>RU</summary>16 Сделать Commit changes (сохранить) изменения на веб интерфейсе.</details> | See in Description |
| <a id='back_task_17_part_1'>17</a>  | [Synchronize external and local JSON repository](#task_17_part_1) <details><summary>RU</summary>17 Синхронизировать внешний и локальный репозиторий JSON</details> | git pull |

### <a id='task_1_part_1'>1. Create an external repository named JSON.</a>  |  [Back to list](#back_task_1_part_1)
#### Description:

Переходим в github по прямой ссылке https://github.com/new и создаем новый репозиторий:
- вводим имя репозитория и убеждаемся что оно доступно
- выбираем тип репозитория Public или Private
- выбираем галочку при создании репозитория автоматически создать файл README.
- .gitignore и license выбираем по необходимости.
- жмем кнопку "Create repository"
- после перенаправляет вашу страницу на созданные репозиторий

![new_repo.gif](assets%2Fimg%2Fnew_repo.gif)

### <a id='task_2_part_1'>2. Clone JSON repository to local machine.</a>  |  [Back to list](#back_task_2_part_1)
Input:
``` bash
git clone https://github.com/MaksimVolkov/json.git
cd json/
ls -la
```

Output:
```
MINGW64 /c/var/1a-testing-course
$ git clone https://github.com/MaksimVolkov/json.git
Cloning into 'json'...
remote: Enumerating objects: 42, done.
remote: Counting objects: 100% (42/42), done.
remote: Compressing objects: 100% (30/30), done.
remote: Total 42 (delta 13), reused 30 (delta 9), pack-reused 0
Receiving objects: 100% (42/42), 5.69 MiB | 7.32 MiB/s, done.
Resolving deltas: 100% (13/13), done.

MINGW64 /c/var/1a-testing-course
$ cd json/

MINGW64 /c/var/1a-testing-course/json (main)
$ ls -la
total 21
drwxr-xr-x 1 Maks 197611    0 Aug 14 21:35 ./
drwxr-xr-x 1 Maks 197611    0 Aug 14 21:35 ../
drwxr-xr-x 1 Maks 197611    0 Aug 14 21:35 .git/
-rw-r--r-- 1 Maks 197611  416 Aug 14 21:35 .gitignore
-rw-r--r-- 1 Maks 197611 8436 Aug 14 21:35 README.md
```

#### Description:



### <a id='task_3_part_1'>3. Inside the local JSON, create the file "new.json".</a>  |  [Back to list](#back_task_3_part_1)
Input:
``` bash
touch new.json
ls

```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ touch new.json
MINGW64 /c/var/1a-testing-course/json (main)
$ ls
README.md  assets  execute_folder  new.json
```

#### Description:



### <a id='task_4_part_1'>4. Add file under git.</a>  |  [Back to list](#back_task_4_part_1)
Input:
``` bash
git add .
or
git add new.json
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ git add .

```

#### Description:

>`git add .` - add all new files
>`git add new.json` - add current file

### <a id='task_5_part_1'>5. Commit file.</a>  |  [Back to list](#back_task_5_part_1)
Input:
``` bash
git commit -m "add new.json"
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ git commit -m "add new.json"
[main c8aada4] add new.json
 4 files changed, 58 insertions(+), 10 deletions(-)
 create mode 100644 new.json
```

#### Description:



### <a id='task_6_part_1'>6. Push file to external GitHub repository.</a>  |  [Back to list](#back_task_6_part_1)
Input:
``` bash
git push
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ git push
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Writing objects: 100% (8/8), 2.05 KiB | 1.03 MiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/MaksimVolkov/json.git
   6e6c7b0..c8aada4  main -> main
```

#### Description:



### <a id='task_7_part_1'>7. Edit the contents of the "new.json" file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.</a>  |  [Back to list](#back_task_7_part_1)
Input:
``` bash
vim new.json
 INSERT
{
  "user": {
    "id":1,
    "name":"Dobby",
    "last_name":"Houseelf",
    "full_name": "Dobby Houseelf Potterovich",
    "age": 30,
    "number_of_pets": 1,
    "desired_salary": 75000
  }}
:wq
ENTER

```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ vim new.json 

```

#### Description:



### <a id='task_8_part_1'>8. Submit changes to external repository.</a>  |  [Back to list](#back_task_8_part_1)
Input:
``` bash
git add .
git commit -m "added content to file new.json"
git push

```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ git add .

MINGW64 /c/var/1a-testing-course/json (main)
$ git commit -m "added content to file new.json"
[main d4e6d36] added content to file new.json
 5 files changed, 107 insertions(+), 23 deletions(-)
 create mode 100644 assets/img/vim_1.jpg

MINGW64 /c/var/1a-testing-course/json (main)
$ git push
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 8 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 23.19 KiB | 7.73 MiB/s, done.
Total 10 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/MaksimVolkov/json.git
   c8aada4..d4e6d36  main -> main

```

#### Description:



### <a id='task_9_part_1'>9. Create preferences.json file</a>  |  [Back to list](#back_task_9_part_1)
Input:
``` bash
touch preferences.json
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ touch preferences.json

```

#### Description:



### <a id='task_10_part_1'>10. In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.</a>  |  [Back to list](#back_task_10_part_1)
Input:
``` bash
vim preferences.json
INSERT
{
  "preferences": {
    "favorite_movie": "Terminator 2",
    "favorite_tv_show": "The Big Bang Theory",
    "favorite_food": "Nepalese",
    "favorite_season": "Summer",
    "desired_travel_destination": "United Kingdom"
  }
}
CTRL+C
:wq
ENTER
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ vim preferences.json
```

#### Description:



### <a id='task_11_part_1'>11. Create a sklls.json file to add information about the skills that will be studied in the course in JSON format</a>  |  [Back to list](#back_task_11_part_1)
Input:
``` bash
touch skills.json
vim skills.json
INSERT
{
  "ru": [
    {
      "title": "Основы работы ...",
      "sections": [{...},{...}]
    }
  ],
  ... see full version in Description..
}
CTRL+C
:wq
ENTER
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ touch skills.json

MINGW64 /c/var/1a-testing-course/json (main)\n$ vim skills.json"
```

#### Description:

```json
{
  "ru": [
    {
      "title": "Основы работы с системой контроля версий Git",
      "sections": [
        {
          "title": "Взаимодействие с веб интерфейсом GitHub",
          "sections": [
            {"title": "Создание репозитория"},
            {"title": "Создание файлов"},
            {"title": "Редактирование файлов"},
            {"title": "Далать Commit changes"}
          ]
        }
      ]
    },
    {
      "title": "Работа с командной строкой",
      "sections": [
        {"title": "Клонирование репозитория на локальное устройство"},
        {"title": "Создание json файлов"},
        {"title": "Редактирование файлов используя vim"},
        {"title": "Использование json синтаксиса"},
        {"title": "git add добавление (индексирование) файлов в локальном Git репозитории"},
        {"title": "git commit - фиксирование изменений в git истории"},
        {"title": "git push - отправка зафиксированных изменений на удаленный репозиторий (GitHub)"},
        {"title": "git pull - получение изменений из удаленного репозитория (GitHub)"}
      ]
    },
    {"title": "Создание отчета проделанной работы"}
  ],
  "en": [
    {
      "title": "Basics of Using Git Version Control System",
      "sections": [
        {
          "title": "Interacting with the GitHub Web Interface",
          "sections": [
            {"title": "Creating a Repository"},
            {"title": "Creating Files"},
            {"title": "Editing Files"},
            {"title": "Making Commit Changes"}
          ]
        }
      ]
    },
    {
      "title": "Working with the Command Line",
      "sections": [
        {"title": "Cloning a Repository to Local Device"},
        {"title": "Creating JSON Files"},
        {"title": "Editing Files Using vim"},
        {"title": "Using JSON Syntax"},
        {"title": "git add - Adding (Indexing) Files to Local Git Repository"},
        {"title": "git commit - Recording Changes in Git History"},
        {"title": "git push - Sending Committed Changes to Remote Repository (GitHub)"},
        {"title": "git pull - Fetching Changes from Remote Repository (GitHub)"}
      ]
    },
    {"title": "Creating a Report of Accomplished Work"}
  ]
}
CTRL+C
:wq
ENTER
```


### <a id='task_12_part_1'>12. Upload 2 files at once to an external repository.</a>  |  [Back to list](#back_task_12_part_1)
Input:
``` bash
git add .
git commit -m "commit multiple files"
git push
```

Output:
```
MINGW64 /c/var/1a-testing-course/json (main)
$ git add .

MINGW64 /c/var/1a-testing-course/json (main)
$ git commit -m "commit multiple files"

MINGW64 /c/var/1a-testing-course/json (main)
$ git push
```

#### Description:



### <a id='task_13_part_1'>13. Create a bug_report.json file on the web interface.</a>  |  [Back to list](#back_task_13_part_1)
Input:
``` bash
See in Description
```

#### Description:

Step 1

![create_new_file.png](assets%2Fimg%2Fcreate_new_file.png)

Step 2

![new_repo.gif](assets%2Fimg%2Fadd_name_file.png)

### <a id='task_14_part_1'>14. Make Commit changes (save) changes on the web interface.</a>  |  [Back to list](#back_task_14_part_1)
Input:
``` bash
See in Description
```

#### Description:

Step 3

![create_new_file.png](assets%2Fimg%2Fcommit_changes.png)

Step 4

![new_repo.gif](assets%2Fimg%2Fcommit_changes_2.png)

Step 5

![new_repo.gif](assets%2Fimg%2Flist_with_bug_report.png)

Step 1-5

![new_repo.gif](assets%2Fimg%2Fcreate-file-github-web.gif)

### <a id='task_15_part_1'>15. On the web interface, modify the bug_report.json file, add a bug report in JSON format.</a>  |  [Back to list](#back_task_15_part_1)
Input:
``` bash
See in Description
```

#### Description:

Step 1

![new_repo.gif](assets%2Fimg%2Fedit_file.png)

Step 2

![new_repo.gif](assets%2Fimg%2Fedit_button.png)

Step 3

![new_repo.gif](assets%2Fimg%2Fadd_report.png)

Step 4

![new_repo.gif](assets%2Fimg%2Fadd_report.png)


### <a id='task_16_part_1'>16. Make Commit changes (save) changes on the web interface.</a>  |  [Back to list](#back_task_16_part_1)
Input:
``` bash
See in Description
```

#### Description:

Step 5

![create_new_file.png](assets%2Fimg%2Fcommit_changes.png)

Step 6

![new_repo.gif](assets%2Fimg%2Fcommit_changes_2.png)


### <a id='task_17_part_1'>17. Synchronize external and local JSON repository</a>  |  [Back to list](#back_task_17_part_1)
Input:
``` bash
git pull
```

#### Description:




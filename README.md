# <a id='back_to_list'>JSON</a>

### <a id='back_to_list_p_1'>JSON </a>

| №  | Title EN | Answer |
|----|----------|--------|
| <a id='back_task_1_part_1'>1</a>  | [Create an external repository named JSON.](#task_1_part_1) <details><summary>RU</summary>Создать внешний репозиторий c названием JSON.</details> |  |
| <a id='back_task_2_part_1'>2</a>  | [Clone JSON repository to local machine.](#task_2_part_1) <details><summary>RU</summary>Клонировать репозиторий JSON на локальный компьютер.</details> | git clone https://github.com/MaksimVolkov/json.git <br />cd json/ <br />ls -la |
| <a id='back_task_3_part_1'>3</a>  | [Inside the local JSON, create the file "new.json".](#task_3_part_1) <details><summary>RU</summary>Внутри локального JSON создать файл "new.json".</details> | touch new.json <br />ls <br /> |
| <a id='back_task_4_part_1'>4</a>  | [Add file under git.](#task_4_part_1) <details><summary>RU</summary>Добавить файл под гит.</details> |  |
| <a id='back_task_5_part_1'>5</a>  | [Commit file.](#task_5_part_1) <details><summary>RU</summary>Закоммитить файл.</details> |  |
| <a id='back_task_6_part_1'>6</a>  | [Push file to external GitHub repository.](#task_6_part_1) <details><summary>RU</summary>Отправить файл на внешний GitHub репозиторий.</details> |  |
| <a id='back_task_7_part_1'>7</a>  | [Edit the contents of the "new.json" file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.](#task_7_part_1) <details><summary>RU</summary>Отредактировать содержание файла "new.json" - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.</details> |  |
| <a id='back_task_8_part_1'>8</a>  | [Submit changes to external repository.](#task_8_part_1) <details><summary>RU</summary>Отправить изменения на внешний репозиторий.</details> |  |
| <a id='back_task_9_part_1'>9</a>  | [Create preferences.json file](#task_9_part_1) <details><summary>RU</summary>Создать файл preferences.json</details> |  |
| <a id='back_task_10_part_1'>10</a>  | [In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.](#task_10_part_1) <details><summary>RU</summary>В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.</details> |  |
| <a id='back_task_11_part_1'>11</a>  | [Create a sklls.json file to add information about the skills that will be studied in the course in JSON format](#task_11_part_1) <details><summary>RU</summary>Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON</details> |  |
| <a id='back_task_12_part_1'>12</a>  | [Upload 2 files at once to an external repository.](#task_12_part_1) <details><summary>RU</summary>Отправить сразу 2 файла на внешний репозиторий.</details> |  |
| <a id='back_task_13_part_1'>13</a>  | [Create a bug_report.json file on the web interface.](#task_13_part_1) <details><summary>RU</summary>На веб интерфейсе создать файл bug_report.json.</details> |  |
| <a id='back_task_14_part_1'>14</a>  | [Make Commit changes (save) changes on the web interface.](#task_14_part_1) <details><summary>RU</summary>Сделать Commit changes (сохранить) изменения на веб интерфейсе.</details> |  |
| <a id='back_task_15_part_1'>15</a>  | [On the web interface, modify the bug_report.json file, add a bug report in JSON format.](#task_15_part_1) <details><summary>RU</summary>На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.</details> |  |
| <a id='back_task_16_part_1'>16</a>  | [Make Commit changes (save) changes on the web interface.](#task_16_part_1) <details><summary>RU</summary>Сделать Commit changes (сохранить) изменения на веб интерфейсе.</details> |  |
| <a id='back_task_17_part_1'>17</a>  | [Synchronize external and local JSON repository](#task_17_part_1) <details><summary>RU</summary>Синхронизировать внешний и локальный репозиторий JSON</details> |  |

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
#### Description:



### <a id='task_5_part_1'>5. Commit file.</a>  |  [Back to list](#back_task_5_part_1)
#### Description:



### <a id='task_6_part_1'>6. Push file to external GitHub repository.</a>  |  [Back to list](#back_task_6_part_1)
#### Description:



### <a id='task_7_part_1'>7. Edit the contents of the "new.json" file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.</a>  |  [Back to list](#back_task_7_part_1)
#### Description:



### <a id='task_8_part_1'>8. Submit changes to external repository.</a>  |  [Back to list](#back_task_8_part_1)
#### Description:



### <a id='task_9_part_1'>9. Create preferences.json file</a>  |  [Back to list](#back_task_9_part_1)
#### Description:



### <a id='task_10_part_1'>10. In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.</a>  |  [Back to list](#back_task_10_part_1)
#### Description:



### <a id='task_11_part_1'>11. Create a sklls.json file to add information about the skills that will be studied in the course in JSON format</a>  |  [Back to list](#back_task_11_part_1)
#### Description:



### <a id='task_12_part_1'>12. Upload 2 files at once to an external repository.</a>  |  [Back to list](#back_task_12_part_1)
#### Description:



### <a id='task_13_part_1'>13. Create a bug_report.json file on the web interface.</a>  |  [Back to list](#back_task_13_part_1)
#### Description:



### <a id='task_14_part_1'>14. Make Commit changes (save) changes on the web interface.</a>  |  [Back to list](#back_task_14_part_1)
#### Description:



### <a id='task_15_part_1'>15. On the web interface, modify the bug_report.json file, add a bug report in JSON format.</a>  |  [Back to list](#back_task_15_part_1)
#### Description:



### <a id='task_16_part_1'>16. Make Commit changes (save) changes on the web interface.</a>  |  [Back to list](#back_task_16_part_1)
#### Description:



### <a id='task_17_part_1'>17. Synchronize external and local JSON repository</a>  |  [Back to list](#back_task_17_part_1)
#### Description:




## Homework GitHub_1
XML
 1. Создать внешний репозиторий c названием XML.

в интерфейсе GitHub создаем репозиторий с названием HW1_GIT_XML

 2. Клонировать репозиторий XML на локальный компьютер.

клонируем репозиторий через Терминал `git clone ссылка на репозиторий`

 3. Внутри локального XML создать файл “new.xml”.

в Терминале переходим в папку репозитория XML (HW1_GIT_XML) и создаем файл hw1_git_new.xml `touch hw1_git_new.xml`

 4. Добавить файл под гит.

в Терминале добавляем файл в индекс `git add hw1_git_new.xml`

 5. Закоммитить файл.

`git commit -m "добавлен файл hw1_git_new.xml"`

 6. Отправить файл на внешний GitHub репозиторий.

`git push`

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

открываем файл на локальной машине, редактируем и сохраняем (например, в pycharm или VSCOde)

 8. Отправить изменения на внешний репозиторий.

`git add hw1_git_new.xml&&git commit -m "в файл hw1_git_new.xml добавлена общая информация о пользователе" && git push`

 9. Создать файл preferences.xml

на локальной машине через Терминал создаем в папке репозитория XML (HW1_GIT_XML) файл hw1_git_preferences.xml `touch hw1_git_preferences.xml`

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате XML.

открываем файл на локальной машине, редактируем и сохраняем (например, в pycharm или VSCOde)

 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

- на локальной машине через Терминал создаем в папке репозитория XML (HW1_GIT_XML) файл hw1_git_skills.xml `touch hw1_git_skills.xml`
- открываем файл на локальной машине, редактируем и сохраняем (например, в pycharm или VSCOde)


 12. Сделать коммит в одну строку.

```
git add hw1_git_preferences.xml hw1_git_skills.xml
git commit -m "добавлено два файла hw1_git_preferences.xml hw1_git_skills.xml"
```

 13. Отправить сразу 2 файла на внешний репозиторий.

`git push`

 14. На веб интерфейсе создать файл bug_report.xml.

````
- заходим в веб интерфейс GitHub
- переходим в репозиторий XML (HW1_GIT_XML)
- создаем файл при помощи add file --> create new file hw1_git_bug_report.xml
````

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

````
- в веб интерфейсе GitHub в нижней части экрана заполняем title коммита (но description сейчас не заполняем, потому что 
коммит простой и в детальном описании нет необходимости)
- оставляем по умолчанию выбранный радиобаттон - commit directly to the main branch (поскольку работаем именно с main)
- в нижней части окна с файлом нажимаем кнопку commit new file
````

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

````
- заходим в веб интерфейс GitHub
- переходим в репозиторий XML  
- переходим в режим редактирования файла hw1_git_bug_report.xml (иконка редактирования в правой части)
- добавляем информацию о баге в формате xml в файл hw1_git_bug_report.xml
````

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```
- в веб интерфейсе GitHub в нижней части экрана заполняем title коммита (но сейчас description не заполняем, потому что коммит простой и в детальном описании нет необходимости)
- оставляем по умолчанию выбранный радиобаттон - commit directly to the main branch (поскольку работаем именно с main)
- в нижней части окна с файлом нажимаем кнопку commit new file
```

 18. Синхронизировать внешний и локальный репозиторий XML

`git pull && git push`

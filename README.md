 1. Создать внешний репозиторий c названием XML.

![image](https://github.com/Abramenkova01/XML/assets/117236113/ff4a618c-630a-4edd-aa54-e62b348c5938)


 2. Клонировать репозиторий XML на локальный компьютер.

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~                     
$ cd Git                                   
(указываем в Git Bash папку на локальном компе)

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git
$ git clone https://github.com/Abramenkova01/XML.git 

(указываем ссылку на внешний репозиторий)

  
 3. Внутри локального XML создать файл “new.xml”.

 Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git
$ cd XML

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ touch new.xml
 

 4. Добавить файл под гит.

 Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ git add new.xml


 5. Закоммитить файл.

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ git commit -m "add new.xml"        
 

 6. Отправить файл на внешний GitHub репозиторий.
  
Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ git push


 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ cat >> new.xml
<about_me>
        <name>Mary</name>
        <age>38</age>
        <pet>none</pet>
        <desired_salary>1000</desired salary>
</about_me>


 8. Отправить изменения на внешний репозиторий.

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ git commit -am "modify new.xml"


Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ git push

9. Создать файл preferences.xml

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ touch preferences.xml

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

 Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ cat >> preferences.xml
<preferences>
        <favourite_movie>Intouchables</favourite_movie>
        <favourite_TV_series>Friends</favourite_TV_series>
        <favourite_food>sushi</favourite_food>
        <favourite_time_of_year>summer</favourite_time_of_year>
        <country_to_travel>Canada</country_to_travel>
</preferences>

 
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

 Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ touch skills.xml

Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ cat >> skills.xml
<skills>
        <skill_1>SDLC</skill_1>
        <skill_2>Agile</skill_2>
        <skill_3>Client_Server</skill_3>
        <skill_4>API</skill_4>
        <skill_5>SQL</skill_5>
</skills>

 
 12. Сделать коммит в одну строку.

 Marie Pyatrouna@DESKTOP-EDQMALU MINGW64 ~/Git/XML (main)
$ git add . && git commit -m "add 2 files"


 34. Отправить сразу 2 файла на внешний репозиторий.
 35. На веб интерфейсе создать файл bug_report.xml.
 36. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 37. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 38. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 39. Синхронизировать внешний и локальный репозиторий XML

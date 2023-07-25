1. Создать внешний репозиторий c названием TXT.
```
NEW - TXT - like [Add a README file] - Create repository
```
2. Клонировать репозиторий TXT на локальный компьютер.
```
git clone https://github.com/Ta2703/TXT.git
```
3. Внутри локального TXT создать файл “new.txt”.
```
 cd TXT / touch new.txt
```
 4. Добавить файл под гит.
```
 git add new.txt
```
 5. Закоммитить файл.
```
 git commit -m "edited the new.txt"
```
 6. Отправить файл на внешний GitHub репозиторий.
```
git push origin main
```
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```
 vim new.txt 
[I]
Name: Tamara
Age: 28
Animal: 1
Salary: 500$
[esc]
:wq
```
 8. Отправить изменения на внешний репозиторий.
```
git commit -a -m "edited the new.txt" && git push origin main
```
 9. Создать файл preferences.txt
```
touch preferences.txt
```
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
vim preferences.txt
[i]
```
```
Favorite Film - Titanic
Favorite Series - Black mirror
Favorite Food - Bananas
Favorite Time - Spring
A side that would like to visit - Spain
```
```
[esc] :wq
```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```
touch skills.txt 
vim skills.txt
[i]
```
```
1. Basic theory (What is testing, bug reports, documentation, types, methods, testing areas, etc.) SDLC, STLC.
2. What is a client-server architecture.
3. HTTP Methods of requests to the server.
4. HTTP server response codes.
5. Structures of HTTP requests and responses.
6. What is JSON, XML. Their structure.
7. API testing via Postman (JS, API autotests).
8. Removing and reading logs from an external server.
9. Sniffing http web traffic via Charles and Fiddler.
10. Dev Tools of web browsers (Google Chrome, FireFox).
11. VPN. (How it works, why you need it, how to use it, tool options)
12. Mobile testing.
13. Feature iOS, Android, guidelines.
14. Building iOS applications on XCode. (Those who do not have a Mac computer, just look)
15. Building Android applications on Android Studio.
16. ADB (android device management).
17. Setting up proxy and vpn on iOS and Android.
18. Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android.
19. Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface)
20. Basics of bash scripting, automation of routine tasks on the server.
21. Access to remote servers.
22. SQL basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. Postgres database (installation, configuration and use).
24. Non-relational database Redis (installation, configuration and use).
25. Load testing in Jmeter.
26. Scrum development methodology.
27. Test Design Techniques (Equivalence Classes, Boundary Values, Combinatorial Techniques (Pairwise, Orthogonal, Basic Choice, Every Choice), States and Transitions)
28.Python. (Learning the basics. Creating a client-server application) 
```
```
[esc] :wq
```

 12. Сделать коммит в одну строку.
```
 git add . && git commit -m "edited the skills.txt"
```
 13. Отправить сразу 2 файла на внешний репозиторий.
```
 git push origin main
```
 14. На веб интерфейсе создать файл bug_report.txt.
```
 add file / create new file
```
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
«bug_report.txt»/ Commit changes
```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```
bug_report.xml / Edit this file 
success - true
user - [object Object]
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT
```
 git pull origin main
```

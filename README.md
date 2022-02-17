# XML
#### 1. Создать внешний репозиторий c названием XML.
* https://github.com/LudaShersh?tab=repositories 
* new
* name:XML
* add a readmefile
* create repository
#### 2. Клонировать репозиторий XML на локальный компьютер.
* code
* https
* copy
* open gitbash
* write: git clone https://github.com/LudaShersh/XML.git
#### 3. Внутри локального XML создать файл “new.xml”.
* cd xml
* vim new.xml
#### 4. Добавить файл под гит.
* git add new.xml
#### 5. Закоммитить файл.
* git commit -m "add 1 file xml"
#### 6. Отправить файл на внешний GitHub репозиторий.
* git push
#### 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
* vim new.xml
```xml
<?xml version = "1.0" encoding = "UTF-8" standalone = "no" ?>
<information about me>
        <full name>Shershneva Ludmila Mikhailovna</full name>
        <age>25</age>
        <number of pets>1</number of pets>
        <future desired job>QA</future desired job>
</informatoin about me>
```
#### 8. Отправить изменения на внешний репозиторий.
* git commit -am"change xml file"   
* git push
#### 9. Создать файл preferences.xml
* vim preferences.xml
#### 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```xml
<?xml version = "1.0" encoding = "UTF-8" standalone = "no" ?>
 <preferences>
        <favorite movie>the pursuit of happyness</favorite movie>
        <favorite TV series>Sherlock</favorite TV series>
        <favorite food>pasta</favorite food>
        <favorite season>summer</favorite season>
        <country I would like to visite>Georgia</country I would like to visite>
</preferences>
```
#### 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
* vim skills.xml
```xml
<?xml version = "1.0" encoding = "UTF-8" standalone = "no" ?>
<skills>
        <item id="1">Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.</item>
        <item id="2">Что такое клиент-серверная архитектура</item>
        <item id="3">HTTP Методы запросов на сервер</item>
        <item id="4">коды ответов HTTP сервера</item>
        <item id="5">Структуры HTTP запросов и ответов</item>
        <item id="6">Что такое JSON, XML. Их структура</item>
        <item id="7">Тестирование API через Postman (JS, автотесты API)</item>
        <item id="8">Снятие и чтение логов c внешнего сервера</item>
        <item id="9">Снифинг http web трафика через Charles и Fiddler</item>
        <item id="10">Dev Tools веб браузеров (Google Chrome, FireFox)</item>
        <item id="11">VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</item>
        <item id="12"> Мобильное тестирование</item>
        <item id="13">Особенность iOS, Android, гайдлайны</item>
        <item id="14">Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</item>
        <item id="15">Сборка Android приложений на Android Studio</item>
        <item id="16">ADB (управление андройд девайсами)</item>
        <item id="17">Настройка прокси и vpn на iOS и Android</item>
        <item id="18">Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android</item>
        <item id="19">Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</item>
        <item id="20">Основы bash скриптинг, автоматизация рутинных задач на сервере</item>
        <item id="21">Доступ к удалённым серверам.</item>
        <item id="22">Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</item>
        <item id="23">База данных Postgres (установка, настройка и использование)</item>
        <item id="24">Нереляционная база данных Redis (установка, настройка и использование)</item>
        <item id="25">Нагрузочное тестирование в Jmeter</item>
        <item id="26">Методология разработки Scrum</item>
        <item id="27">Python. (Изучение основ. Создание клиент серверного приложения)</item>
</skills>
```
#### 12. Сделать коммит в одну строку.
* git add . && git commit -m "add ppregerences and skills file xml"
#### 13. Отправить сразу 2 файла на внешний репозиторий.
* git push
#### 14. На веб интерфейсе создать файл bug_report.xml.
* add file
* create new file
### 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* commit change
#### 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```xml
<?xml version = "1.0" encoding = "UTF-8" standalone = "no" ?>
<bug_report>
  <item id="1">Summary</item>
  <item id="2">Description</item>
  <item id="3">Step to reproduce</item>
  <item id="4">Severity</item>
  <item id="5">Priority</item>
  <item id="6">Envirenmen</item>
</bug_report>
```
#### 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* commit change
#### 18. Синхронизировать внешний и локальный репозиторий XML
* git pull

https://github.com/LudaShersh/XML

# XML
Создать внешний репозиторий c названием XML.
new repository 
create repository
  Клонировать репозиторий XML на локальный компьютер.
$ git clone  git@github.com:JackBlaaack/XML.git
 Внутри локального XML создать файл “new.xml”.
touch new.xml
  Добавить файл под гит.
$git status 
$git add .
 Закоммитить файл.
$git commit -m "Adding new.xml"
  Отправить файл на внешний GitHub репозиторий.
git push
 Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
<?xml version="1.0" encoding="UTF-8"?>
<new>
        <name>Jack</name>
        <age>27</age>
        <countofpets>0</countofpets>
        <countofpets>0</countofpets>
	<futurewishsalary>1500</futurewishsalary>
</new>

 Отправить изменения на внешний репозиторий.
git add .
git commit -m "Writing  the information in the new.xml"
git push
 29. Создать файл preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
<?xml version="1.0" encoding="UTF-8"?>
<preferences>
        <favoritefilm>Alone at home</favoritefilm>
        <favoriteserial>The theory of big bang</favoriteserial>
        <favoritefood>meat in french</favoritefood>
        <favoritetimeofyear>Spring</favoritetimeofyear>
        <favoritecountry>The USA</favoritecountry>
</preferences>
Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
touch skills.xml
Сделать коммит в одну строку.
git status
git add .
git commit -am "Adding 2 new files"
 Отправить сразу 2 файла на внешний репозиторий.
git push
  На веб интерфейсе создать файл bug_report.xml.
  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Add the bug report.xml
Writing the information in the bug report.xml
 На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<?xml version="1.0" encoding="UTF-8"?>
<bug_report>
  <Summary>Menu:error, at the entrance</Summary>
  <Type>Bug</Type>
    <Priority>Medium</Priority>
  <Severity>Major</Severity>
  <AffectsVersion>1.0</AffectsVersion>
  <Enviroment>Windows 10 Pro, Google Chrome 98</Enviroment>
    <Description>
    <FirstStep>Open web-site</FirstStep
    <SecondStep>pass authorization",
    "ThirdStep": "Press the button Menu</SecondStep>
    <FourthStep>Pay attention to the screen</FourthStep>
    <ExpectedResult>Press the button Menu and see categories of products",
    "Result": "Press the button Menu and see eror</ExpectedResult>
  </Description>
    <Status>Open</Status>
    <TypeofBug>Functional</TypeofBug>
</bug_report>
 Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Writing the information in the bug report.xml
 Синхронизировать внешний и локальный репозиторий 
git fetch 
git pull 
git push

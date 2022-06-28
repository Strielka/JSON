1. Клонировать репозиторий JSON на локальный компьютер.
	git clone https://github.com/Strielka/JSON.git
2. Внутри локального JSON создать файл “new.json”.
	cd JSON
	vim new.json
3. Добавить файл под гит.
	git add new.json
4. Закоммитить файл.
	git commit -m "improve myself"
5. Отправить файл на внешний GitHub репозиторий.
	git push
6. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
	{
        "name": "Lana",
        "age": 23,
        "pets": 1,
        "future desired salary": 500
	}
7. Отправить изменения на внешний репозиторий.
	git commit -am "add modify new.json"
	git push
8. Создать файл preferences.json
	vim preferences.json
9. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, стрaна которую хотели бы посетить) в формате JSON.
	{   "favourite film": "The Call",
        "favourite serial": "Chernobyl: Zone of Exclusion", "To the Lake (Epidemic)",
        "favourite food": "cottage cheese casserole",
        "favorite season": "summer",
        "country I  would like to visit": "USA"
	}
10. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
	vim skills.json
	{
        "s1": "Linux_terminal_(GitBash)_commands",
        "s2": "Visual_Studio_Code",
        "s3": "JS_functions",
        "s4": "Chai_JS",
        "s5": "Postman",
        "s6": "Git_Draw",
        "s7": "Git_branch_merge",
        "s8": "ClientServer",
        "s9": "Postman_scripts_environment",
        "s10": "Form_testing"
}

11. Отправить сразу 2 файла на внешний репозиторий.
	git add .
	git commit -m "preferences & skills"
	git push
12. На веб интерфейсе создать файл bug_report.json.
13. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	https://i.imgur.com/D4BIdXP.png
	https://i.imgur.com/PoTlLGR.png
14. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	"№": "1",
	"Bug summary": "In the `Apple` category GET request takes a long time to load",
	"Severity": "minor",
	"Priority": "middle",
	"Steps to reproduce": "1. Go to  https://www.ebay.com/b/Apple/bn_21819543 2. Open field `Network` in DevTools  3. Check the timings of GET requests",
	"Actual result": "Slow server response time (1107 ms)",
	"Expected result": "The recommended limit is 500 ms",
	"Assignee": "Developer 1",
	"Attachment": "https://i.imgur.com/UADVqcg.png, https://i.imgur.com/sS09uxg.png"
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
16. Синхронизировать внешний и локальный репозиторий JSON
	git pull

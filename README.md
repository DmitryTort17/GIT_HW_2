# GIT_HW_2
1. На локальном репозитории сделать ветки для:
- Postman - git branch<имя_ветки>
- Jmeter - git branch<имя_ветки>
- CheckLists - git branch<имя_ветки>
- Bag Reports - git branch<имя_ветки>
- SQL - git branch<имя_ветки>
- Charles - git branch<имя_ветки>
- Mobile testing - git branch<имя_ветки>

2. Запушить все ветки на внешний репозиторий
- git push -u origin <имя_ветки>
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
- git branch Bug_reports
- cat > bug_report_structure.txt
4. Запушить структуру багрепорта на внешний репозиторий
git add bug_reports_structure.txt
git commit -m "структура баг репорта"
git push
5. Вмержить ветку Bag Reports в Main
git checkout Main
git merge Bug_reports
6. Запушить main на внешний репозиторий.
Git push
7. В ветке CheckLists набросать структуру чек листа.
- git branch CheckLists
- cat > structure_CheckList.txt
8. Запушить структуру на внешний репозиторий
git add structure_CheckList.txt
git commit -m "структура чеклиста"
git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main
git checkout main
git pull
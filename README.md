# HM-2-git_branching
# Предварительные шаги , перед созданием веток на лоокальном репозитории: 
- Создаем удаленный репозиторий в github: HM-2-git_branching
- копируем HTML-ссылку на удаленный репозиторий
- клонирование этого репозитория
-  ![Screenshot_1](https://user-images.githubusercontent.com/130314205/236188602-00111a7e-1f28-4d80-8524-3ad8f5a3f8a9.png)
# 1.На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
- Заходим в эту папку : 
![Screenshot_2](https://user-images.githubusercontent.com/130314205/236189479-74bfda68-64e3-4dbd-83ec-433e4ea75b53.png)
- Проверяем, что мы в ветке main:
![image](https://user-images.githubusercontent.com/130314205/236189752-31b07a9c-120d-4b19-9288-c7cea6767e99.png)
- Создаем ветки: git branch Postman,
git branch Jmeter,
git branch CheckLists,
git branch Bag_Reports,
git branch SQL,
git branch Charles,
git branch Mobile_testing.
- Проверяем, все ли ветки созданы:

![image](https://user-images.githubusercontent.com/130314205/236190641-874bb751-9268-4592-94ee-47b1dec0eae3.png)
# 2. Запушить все ветки на внешний репозиторий. Это действие делается командой git push -u origin <название ветки>. Для выполнения задания выполнено 7 команд. Вот пример первой команды:
 ![image](https://user-images.githubusercontent.com/130314205/236192938-8df8aac4-3c80-433e-845b-d340e308d22d.png)
# 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта. Для этого нужно сначала перейти в ветку Bag Reports:
 ![image](https://user-images.githubusercontent.com/130314205/236194161-604108f2-99bc-453f-b334-83b52b88c2d2.png)
- Убедиться , что находимся в нужной ветке:

 ![image](https://user-images.githubusercontent.com/130314205/236194373-33412664-6c7f-4fd2-936a-3ee1a2d5c271.png)

- Создаем файл bug_report.txt :

![image](https://user-images.githubusercontent.com/130314205/236194779-b587cf36-7062-4b40-b533-69d904145125.png)
- Вносим в него структуру баг репорта: 

![image](https://user-images.githubusercontent.com/130314205/236195046-05bac9f2-a953-46ef-b4d5-1a272a1b1de2.png)
# 4. Запушить структуру багрепорта на внешний репозиторий. Для этого нужно выполнить команды:
- git add .
- git commit -m "bug_report"
- git push
 
 ![image](https://user-images.githubusercontent.com/130314205/236196274-045a82d1-f45d-4e94-99cc-381e5d95468a.png)

# 5. Вмержить ветку Bag Reports в Main. 
- Для этого нужно вернуться из ветки Bag Reports в ветку Main: 
 
 ![image](https://user-images.githubusercontent.com/130314205/236197040-fa215422-feb5-4648-a0fd-512680a3a09f.png)
- и добавляем изменения ветки Bag Reports в ветку Main:
 
 ![image](https://user-images.githubusercontent.com/130314205/236197404-1de97d27-db72-4068-b1ad-28f9c9fd759f.png)
# 6. Запушить main на внешний репозиторий.
![image](https://user-images.githubusercontent.com/130314205/236197700-14b360e6-b716-4c08-ba63-8a22ae178951.png)
# 7. В ветке CheckLists набросать структуру чек листа.
- Для этого нужно прейти из ветки Main в ветку CheckLists:
 
 ![image](https://user-images.githubusercontent.com/130314205/236198045-2d43dec4-38fc-4c9e-9fbf-f6a54c4045ac.png)
- Создаем текстовый файл checkList.txt:
 ![image](https://user-images.githubusercontent.com/130314205/236198448-0344da1e-aaa0-4953-abf4-687708ca8679.png)
- Вносим с него структуру чек листа:
 ![image](https://user-images.githubusercontent.com/130314205/236198599-dca1c283-1d45-4a86-9e1b-6da783b44856.png)
# 8. Запушить структуру на внешний репозиторий.
- Для этого нужно выполнить команды:
- git add .
- git commit -m "checkList"
-  git push

![image](https://user-images.githubusercontent.com/130314205/236199192-444ae160-abf5-4719-bbfa-7608038faf66.png)
# 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.
- Для этого нужно перейти на сайт GitHub.com , зайти на репозиторий HM-2-git_branching,
- Стать на ветку CheckLists
- Нажать Compare & pull request чтобы открыть запрос на извлечение
- Нажать на Create pull request
- Перейдите на следующую страницу объединения, 
- Нажать на Merge pull request и Confirm merge.
 # 10. Синхронизировать Внешнюю и Локальную ветки Main.
 - Для этого нужно перейтис с ветки CheckLists в ветку Main.
 
 ![image](https://user-images.githubusercontent.com/130314205/236200860-45ad4a69-9fc1-4567-a025-6c935166e0c9.png)
- Синхронизировать внешнюю и локальную ветки Main.

![image](https://user-images.githubusercontent.com/130314205/236201091-465244e8-8204-466f-96ba-e6fe08b9ffa3.png)

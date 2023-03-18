#### 1. На локальном репозитории сделать ветки для:
##### Зоходим в папку main и там создаем новые ветки > git checkout main
 ###Postman      
  git branch Postman,  
 Jmeter       === git branch Jmeter,         
 CheckLists   === git branch CheckLists,    
 Bag Reports  === git branch Bag Reports,  
 SQL          === git branch SQL,            
 Charles      === git branch Charles,         
 Mobile testing === git branch Mobile testing,  

2. Запушить все ветки на внешний репозиторий  
	=== git push -u origin --all
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
	=== touch test.txt
	=== vim test.txt
	 Шаги для воспроизведения:
                 1. Открыть
                 2. Кликнуть
                 3. Ввести в поле значение N1
                 4. Ввести в поле значение N2
                 5. Кликнуть кнопку Calculate

                 Результат:
                 В поле Result отображается V1.

                 Ожидаемый результат:
                 В поле Result отображается V2.

4. Запушить структуру багрепорта на внешний репозиторий 
	=== git add .
	=== git commit -m "bag repotrs file"
	=== git push
5. Вмержить ветку Bag Reports в Main 
	===git checkout main (переходим в ветку main, и уже туда мержем ветку баг репортс)
	=== git merge Bag_Reports
6. Запушить main на внешний репозиторий. === git push
7. В ветке CheckLists набросать структуру чек листа. === touch check_lists.txt
8. Запушить структуру на внешний репозиторий
	=== git add .
	=== git commit -m "checklists file"
	=== git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
	=== https://github.com/P-e-t-e-r-Parker/group26_petr/tree/CheckLists
	=== Compare & pull request
	=== Create pull request
	=== Merge pull request
   	=== Confirm merge
10. Синхронизировать Внешнюю и Локальную ветки Main	
	=== git pull	

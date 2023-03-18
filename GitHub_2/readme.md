#### :heavy_check_mark: 1. На локальном репозитории сделать ветки для:
###### Зоходим в папку main и там создаем новые ветки 
	git checkout main
 ##### :heavy_check_mark: Postman      
 	git branch Postman,  
 ##### :heavy_check_mark: Jmeter        
 	 git branch Jmeter,         
 ##### :heavy_check_mark: CheckLists     
 	git branch CheckLists,    
 ##### :heavy_check_mark: Bag Reports   
 	 git branch Bag Reports,  
 ##### :heavy_check_mark: SQL            
 	git branch SQL,            
 ##### :heavy_check_mark: Charles       
 	 git branch Charles,         
 ##### :heavy_check_mark: Mobile testing   
 	git branch Mobile testing,  

#### :heavy_check_mark: 2. Запушить все ветки на внешний репозиторий  
	 git push -u origin --all
#### :heavy_check_mark: 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта:
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
		 
	 touch test.txt
	 vim test.txt


#### :heavy_check_mark: 4. Запушить структуру багрепорта на внешний репозиторий 
	 git add .
	 git commit -m "bag repotrs file"
	 git push
#### :heavy_check_mark: 5. Вмержить ветку Bag Reports в Main 
	git checkout main (переходим в ветку main, и уже туда мержем ветку баг репортс)
	 git merge Bag_Reports
#### :heavy_check_mark: 6. Запушить main на внешний репозиторий. === git push
#### :heavy_check_mark: 7. В ветке CheckLists набросать структуру чек листа. === touch check_lists.txt
#### :heavy_check_mark: 8. Запушить структуру на внешний репозиторий
	 git add .
	 git commit -m "checklists file"
	 git push
#### :heavy_check_mark: 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
	 https://github.com/P-e-t-e-r-Parker/group26_petr/tree/CheckLists
	 Compare & pull request
	 Create pull request
	 Merge pull request
   	 Confirm merge
#### :heavy_check_mark: 10. Синхронизировать Внешнюю и Локальную ветки Main	
	 git pull	

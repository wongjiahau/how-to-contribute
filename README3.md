## 5. Modify a file (or add a new file)
Now, since the intention of creating this branch is to add a new feature, I will modify a file to add the new feature.   
In this case, I will modify the file named `README.md`.  
  
*NOTE: You can modify the file which any IDE or any text editor you want, just remember to click SAVE after you edit.*
  
After you modified the file, go to the Git Bash console again, then type in :  
```
git status
```  
This command will tell you what have been modified in this repo :   

![image](https://user-images.githubusercontent.com/23183656/31303632-78427408-ab43-11e7-920e-52f1bb36bbb2.png)

## 6. Commit the changes to your branch
##### 1. Before you commit, you have to *stage* the changes : 
```
git add .
```
The dot at the end is a neccessity, and the space is required, so the command should resemble this `git<space>add<space>.`
  
  FYI, the command above will stage ALL changes. But, what the heck is this *staging* thingy? No worries, you can learn it **[HERE](https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git/119790)**.  
  ##### 2.Now, check the git status *again* : 
```
git status
```
Then you shall see this : 

![image](https://user-images.githubusercontent.com/23183656/31303743-e64d1754-ab44-11e7-9fd6-7df19d86a97f.png)

##### 3. Commit the changes : 
```
git commit -m "Modified README.md"
```
You can replace those words within the double quote with your own sentence, but make sure it is meaningful.   
Click **[HERE](https://who-t.blogspot.my/2009/12/on-commit-messages.html)** to learn how to write **good** commit messages.

## Click **[HERE](https://github.com/wongjiahau/how-to-contribute/blob/master/README4.md)** to proceed to Step 7.


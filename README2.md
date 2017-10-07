 ## 3. Create a new branch. 
 In the Git Bash console, type in the following command : (make sure you are in the same console just now)
 1. You need to go into the directory of the project you cloned just now. (Since I had cloned the Apple's Swift repo, so the project folder name is `swift`). FYI, `cd` is a UNIX command which means Change Directory.
 ```
 cd swift
 ```
 2. After that, type in the following command to create a new branch.
 ``` 
 git branch adding-new-feature
 ```
 You can replace the term `adding-new-feature` with other words, but make you don't have any whitespaces in it.  
 If you want to understand more about *branch*, read it **[here](https://backlogtool.com/git-tutorial/en/stepup/stepup1_1.html)**.  
 After you type those commands, the console should look like this:  
 
 ![image](https://user-images.githubusercontent.com/23183656/31303457-843d2cf6-ab40-11e7-8025-cc1095052c41.png)
 
 Notice that the blue word `master` indicate that you are in the `master` branch currently.
 
 ## 4. Checkout into the newly created branch
 This step is fairly simple, you just have to type in the following command.  
 ```
 git checkout adding-new-feature
 ```
Then, the console should look like this: 

![image](https://user-images.githubusercontent.com/23183656/31303504-4bd60634-ab41-11e7-9250-e8f25aeaefce.png)

The blue word `adding-new-feature` indicate that you are in the `adding-new-feature` branch. 

## Click **[here](https://github.com/wongjiahau/how-to-contribute/blob/master/README3.md)** to proceed to step 5.

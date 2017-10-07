## 7. Push the commit(s) to your fork
This step will be slight longer, so please bare with me. 
#### 1. Set the remote URL for your the original repo : 
NOTE : *Original* means the one you forked from. 
```
git remote set-url origin https://github.com/apple/swift.git
```
This command will set the `origin` to be pointing at the link  https://github.com/apple/swift.git. 

#### 2. Set the remote URL for your fork.
```
git remote add myfork https://github.com/wongjiahau/swift.git
```
Notice that the link should contain your username.

#### 3. Push the commit to your fork. 
```
git push myfork <name-of-your-branch>
```
In this case, I will type : 
```
git push myfork adding-new-feature
```
NOTE: Make sure you are in the new branch. 

## 8. Create pull request 
##### 1. Go to the website of your fork, then you will see a `Compare & pull request` button. Click on it.

![opera snapshot_2017-10-07_101717_github com](https://user-images.githubusercontent.com/23183656/31304126-8fcc292a-ab4d-11e7-836a-25793f8e7019.png)

##### 2. Then, click on `Create pull request` button. 

![opera snapshot_2017-10-07_105322_github com](https://user-images.githubusercontent.com/23183656/31304133-cd15039c-ab4d-11e7-9dd6-079beeb39c60.png)

##### 3. All you have to do now is wait for the owner of the repo to review your pull request. 
The owner might do the following action on your pull request :  
a. Merge it to the master branch  
b. Request for changes  
c. Close it

## Click **[HERE](https://github.com/wongjiahau/how-to-contribute/blob/master/README5.md)** for the last step.

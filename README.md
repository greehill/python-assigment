# greehill Python Developer Assignment

Welcome to this round of your interview process.

## The problem

We have n folders, this folders should be synchronized. The folder can have subfolders, so the synchronization should be recursive. 
The rules:
* if a new file or folder added into one of the folder, it should be appeared in the other folders as well
* if a file or folder deleted from in one of the folders, it should be removed from all of the folders
* if one of the file is changed, the change should be applied in all others folders
* if the same file or folder has been changed, the last change shall be applied on all of the folders
* the occurrence of he same file are modified in multiple folder in the exact same time is negligeble 

## Your task

Your task is to create **python package** that implement the above functionality. Monitoring the changes and applying the modification should be considered a consumer-producer problem (hint: use the multiprocessing module to solve it). 


### Requirements

#### Minimum

- It should be a python module, which can be installed
- You must use only the Python standard library (except for the task in the extras)
- You should use multiprocessing module, or have a good argument why you not use it and why your solution is better without multiprocessing
- Please write **clean code** with a quality you'd push to your workplace's repo.
- **Tests are very welcome!** 
- Please use `git`. Reasonable sized commits with reasonable commit messages are preferred (not mandatory), so we can see how you've worked your way towards the result.
- Please push your repo to any mainstream hosting service (**GitHub, GitLab, Bitbucket**), and send it to us **when you are done working on it**. If you are concerned about making your repo public, you can keep it private. Please use GitHub or GitLab, and add @ bertabejnamin and @viktorkovesd as collaborators **after you finished**.

#### Optional

- Synchonize between a local folder and an Azure blob storage. If you are in this stage of the homework and interested to do please get in touch with us, and we can grant you access a little blob storage, which you can use to test your code. 


**Thank you a lot for your time, and have fun with the project! We can't wait to see your work! `{´◕ ◡ ◕｀}`**


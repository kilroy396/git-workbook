1) Add multiple files to your project directory, and run git status
2) Do git add for just ONE of your files
3) Run git status, then commit your changes as before, and run git status again (spotting a theme here?)

```
> touch keeping-your-changes-under-control
> git status                                                                          
On branch master                                                                      
Your branch is ahead of 'origin/master' by 2 commits.                                 
  (use "git push" to publish your local commits)                                      
Untracked files:                                                                      
  (use "git add <file>..." to include in what will be committed)                      
                                                                                      
        keeping-your-changes-under-control                                            
                                                                                      
nothing added to commit but untracked files present (use "git add" to track)                                 
                                                                                      
woodalan@RUBD0DUP2N C:\Users\woodalan\Documents\Development\git-workbook\assignments  
> git add keeping-your-changes-under-control                                          
                                                                                      
woodalan@RUBD0DUP2N C:\Users\woodalan\Documents\Development\git-workbook\assignments  
> git status                                                                          
On branch master                                                                      
Your branch is ahead of 'origin/master' by 2 commits.                                 
  (use "git push" to publish your local commits)                                      
Changes to be committed:                                                              
  (use "git reset HEAD <file>..." to unstage)                                         
                                                                                      
        new file:   keeping-your-changes-under-control                                
                                                                                      
                                                                                      
woodalan@RUBD0DUP2N C:\Users\woodalan\Documents\Development\git-workbook\assignments  
> git commit -m "created file keepiong-your-changes-under-control                                            
```
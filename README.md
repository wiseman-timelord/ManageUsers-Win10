# ManageUsers-Win10
PowerShell User Management Tool
Status: Piece of cake, still cooking.

### Description:
While attempting to add a user, to be able to open up a window, that I can dedicate to a task with relating input controlled through scripts,  I was suddenly unable to add a new user for the thing to log-in, thereabouts, lets remember, we are still one user. I noticed since windows 10, the adding of new users is an online affair, and yet, its possible to do it locally with a few commands in powershell...hence, this tool does that with one of my nice menus for improved user experience.

### Preview:
- Menu Etc...
```
========================================================================================================================
     ManageAccounts-Win10
========================================================================================================================

1. Add an Account

2. Remove an Account

------------------------------------------------------------------------------------------------------------------------

    Current User Accounts:
    UserName1 - Administrator
    UserName2 - Non-Admin
    UserName3 - Administrator

========================================================================================================================
Selection; Menu Options = 1-2, Exit Program = X: 

```
- Simulation
```
Enter the username: NewUser
Enter the password: ********
Should the user be an Administrator? (Y/N): Y
User 'NewUser' created successfully.
User 'NewUser' added to the Administrators group.
```


### Notation:
- Why would I want do do this? because the alternative is emulation, and that is always a little slower, as well as an additional resource usage of memory and disk space. 
- Simiar thing to the online install of .net 3.5, when you can just do it off the iso with a powershell command (see my other tool somewhere if I uploaded it, or otherwise it should be merged). 

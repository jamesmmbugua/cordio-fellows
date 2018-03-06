# cordio-fellows
testing github with cordio fellows

##Tutorials on Rmarkdown and Github

***Personal Notes***

Rmarkdown is a text editor that documents coded results in vaious file formats i.e. pdf, html etc.
To start Rmarkdown project, click on file, new project, RMarkdown. A window will pop up prompting you to add the title and author of the project. You can fill in these details at this stage or just accept the defaults and preoceed to edit them on R Studio console.
You can read more about RMarkdown here <https://www.youtube.com/watch?v=OtiiQ4JVVmc&index=2&list=PLX7J3qtjcll_4s2oaKHuWdRdBMJz7tBAU>

##Introduction to Git and GitHub
Git is a version control ware that must be installed in your computer so as to link/complement R and Rstudio to execute function through Github. On the other hand Github, is a crowd repository that works in the same way as e.g. ***DropBox***.It helps in documenting code versions by simply creating nd building scripts without saving multiple files for each new update.
To interact with Github from R console/Studio, you need to download Git here <a href="https://git-scm.com/download/win">for windows</a>

##Installing Git and setting commiting to global repository/ configuring your account

*Download and run Git exe/dmg file on your PC accepting all default settings
*Configuring your global account
+Open Git CMD/windows/mark terminal and run the following commands:
++Check version type ***git version*** and hit enter
++Configuring your acccount to gloabal setting  type ***git config --global user.name add your github user name***
++Configure your email to gloabal setting type ***git config --global user.email jamesmmbugua@gmail.com***
++View is your settings are successful by displaying the list of command items learn. To do this, type ***git config ist*** a list will display. Confirm that your
***user email*** 
and ***user name*** are appearing in the list. If so, your account have been configured correctly.

##Working with Github
To begin working with Github,
*log in to your account and follow these steps
+Click the drop down arrow on the right of your profile icon/picture
+select and click profile. This will open your profile page
+On the top menu bar, clik on ***repositories*** this should display the number of repository you are working on incase of any and will be 0 if its your first time you are doing this.
+On clicking repositories, a new window will appear with a green button labeled ***New*** on the far right. Click on this button to create a new repository.
++fill in the required details, begining with a new short file name. Note that it somehow not easy to change the name of the repository after creating it. ***Need to find out why?***
+Click ***Initialise with a read me text*** and click create repository.

##Cloning your repository in R
After creating your repository, it will appear as a hyper link on your repository profile. Click on the hyperlinked name to open the repository and do the following:
+Click on ***Clone*** button. This is the green button on the extreme right.
+Copy the link to clip board and move/open R studio

#In R Studio do the following
+Open a new project file by clicking file, new project,


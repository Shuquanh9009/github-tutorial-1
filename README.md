# GitHub Tutorial

_by Jagger D'Ugo_

---
## Git vs. GitHub

Git is version control, like taking snapshots of code.  
Github is a cloud for git, which allows us to see these snapshots. It also has the added bonus of being a great way for people to collaborate with each other on their code as well.  

> A good way to think of the two is like Git being a photographer who takes photos, where Github is like the album where you keep all the photos you've taken.

---
## Initial Setup

Before doing anything else, you'll need to have an IDE, and a Github account.  
There are several IDEs to choose from, but there's only one Github.  
To make a Github account, you first need to navigate to Github and click the create an account icon.  
From there, follow the steps, making sure to use your HSTAT email username if you're from HSTAT.  
Once you're done there, you can get your SSH key set up.
> For those who don't know, an SSH key is used because it is a "Secure Shell", which means that it will keep your files scure even if your network isn't.  
> It's also great becuase you won't need to log in every time you want to access what you use SSH with, which makes getting into your IDE's code way easier.  

To do that, you'll want to follow these steps:
1. Look at the top right corner, and click the profile icon, and navigate to settings.
2. On the left sidebar, click on SSH and GPG.
3. Assuming you're using Cloud9, add the title "cloud9" to the setup.
4. Continuing with this assumption, go to your Cloud9, and find the gear icon on the top right, and go to the SSH keys tab.
5. After that, copy and paste the second SSH key into Github (it should start with ssh-rsa), and then add your SSH key.
6. Once you're done all that, you should see "Hi <your username>! You've successfully authenticated, but GitHub does not provide shell access._" in your c9, after inputting "ssh -T git@github.com"

After finishing that, you're ready to move on to your **Repository Setup!**

---
## Repository Setup

If you're ready to make a repository, you'll first want to navigate to your IDE (we'll continue to use Cloud9 as the example), and get into whatever folder you want to work in.
Simply enter in `git init`, and your folder will be converted into a repository.  
What this now means is that your "repo" can save changes to github, and you can even see these when logged in.
> Note: Make sure you use `git init` within the actual folder you want to work in, not your whole workspace, otherwise you'll have to commit changes within every folder you have, instead of being able to do it with individual repos.  

Now that you've initialized, try creating a file (we'll use a basic text file for this example), and add something to it.  
After doing this, you'll want to add this file to the stage.  
Going back to our photograph analogy from before, adding a file to the stage is like moving it into the shot the photographer will take.  
To do this, type in `git add <filename>`, with `<filename>` being whatever you've called the file.

With the file on the stage, you can now "commit" your changes, which is 

---
## Workflow & Commands



---
## Rolling Back Changes
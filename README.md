# GIT_and_GITHUB

**Your Identity**
The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:

**$ git config --global user.name "mthengne"**

**$ git config --global user.email mthengne1@gmail.com**

Again, you need to do this only once if you pass the --global option, because then Git will always use that information for anything you do on that system. If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.

You can view all of your settings and where they are coming from using:

**$ git config --list --show-origin**

Pull operation using git pull command

**git pull https://github.com/mthengne/Terraform-AWS.git**


  git pull https://github.com/mthengne/Terraform-AWS.git
  
  516  ls -la
  
  517  less README.md
   
  520  vi README.md
  
  521  git status
  
  522  git add README.md
  
  523  git commit
  
  525  git status
  
  526  git commit -m "added content" README.md
  
  528  git remote add  origin "https://github.com/mthengne/Terraform-AWS.git"
  
  529  git push -u origin master


# Team Frankenbot's website repository
Created with Hugo and the Hugo Agency Theme (https://github.com/digitalcraftsman/hugo-agency-theme)

## Installing Hugo:
* Go to the Hugo webpage on installation: https://gohugo.io/getting-started/installing/
* Select your operating system from the list under "**What's on this page**" and follow the instructions

## Prepare your local website repo:
**NOTE** I followed instructions from the following video: https://www.youtube.com/watch?v=oUjk6wpJn7I
* Go to your terminal (bash if using Windows) and go to your working directory (i.e. where you want your project to be located)
  * Example: I want my local repository to be in the directory ~/WebDev/frankenbot/ so I would type:
  ```
  cd ~/WebDev/frankenbot/
  ```
* Make a new directory `mkdir` called `website`; this is where your local git repository will be created
  ```
  mkdir website
  ```
* Go into the `website` directory and create a new site using Hugo
  ```
  cd website
  hugo new site .
  ```
  **NOTE** Now if you type `ls` (which means "list"), you can see all the files and folders in `website`
* Initialize a new git repository in this `website` directory, and associate it with the online website repo
  ```
  git init
  git remote add origin https://github.com/frankenbot/website.git
  ```
* Pull the contents of the `website` repository on GitHub
  ```
  git pull origin master
  ```
  
## Using Hugo:
Now that you have created your local `website` repo, try running it locally on your browser:
* In your local `website` repo, type
  ```
  hugo server
  ```
* Open your web browser and type the following url: http://localhost:1313/
  * You should see your website pop up!
 
## Editing the Website:
This website is made using the Hugo Agency Theme: https://github.com/digitalcraftsman/hugo-agency-theme. 
Follow the instructions in the README file in the hugo-agency-theme GitHub repo for details on how to edit website content 
using this specific theme.


**NOTE** Changes that you make to the website repo do not automatically update the public webpage at https://frankenbot.github.io .
When you are happy with how the website looks and want to update it on the public domain, follow the instructions in the README file
in the `frankenbot.github.io` repository.


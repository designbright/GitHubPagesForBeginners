# GitHubPagesForBeginners
Learn how GitHub pages works and why it's important for every front-end project
*Note this process assumes the user already has a basic understanding of how GitHub (in general) works. 

## What is GitHub Pages?
GitHub Pages (aka GH-Pages) is a way to create a website URL for people to easily view your raw HTML/CSS code as an actual website in a browser. GH-Pages is useful for front-end projects that are more visual in nature. GH-Pages is also useful if you are looking for a new job and you want employers to easily be able to see your projects in a browser. 

Pushing your project files to GitHub will display all the code in your HTML and CSS files. However, people won't be able to see the final product in the form of an actual website unless they cloned/forked your GitHub repo.

For example, you create an awesome website with HTML and CSS. You are able to test your code files on your computer in the browser and see what is actually rendering to the page. However, if you were to send your HTML file to someone, they would not be able to see the website. This is because you would be sending the file path from YOUR computer, which is not something your end user has access to. 

## HOW TO USE GH-PAGES
Create a GitHub repository and make sure all of your project files are up to date
  **Double check that your project contains an index.html file. If it does not, only the README will render to your GH-Pages. 
  
Connect your repo to your computer 

### In Terminal (aka Command Line)
Traverse to your project folder and type:
  ### git status
   The terminal response will say "on branch master", "your branch is up to date with origin/master"
 
 To check which GitHub branch you are currently on type: 
  ### git branch
  
 To create the GH-Pages branch, type:
  ### git branch gh-pages
  
 Switch to the gh-pages branch you just created by typing:
  ### git checkout gh-pages
  
 Push project files to gh-pages, type:
  ### git push origin gh-pages
 
 ### In your browser, type:
  username.github.io/nameofghrepository

#### Replace 'username' with your GitHub username and replace 'nameofghrepository' to the EXACT name of the GH Repository where you created your GH-Pages. This is case and character sensitive so if you get an error in the browser, check that you spelled the name correctly
  
 ## Make your GitHub life easier
Your GitHub repo names and your project folder name should match each other. This helps keep you organized when you are ready to push your files to GitHub. You won't spend hours trying to figure out which files on your computer match the GitHub repo you created. 

### Repo Naming
Name your GH repos as something that relates to the overall topic of your project. This helps other GitHub users easily figure out the purpose of your repo and makes it more likely for them to use it.

### Add READMEs! I heart README's! 
Before starting a project, add a README file. Writing code is hard enough as it is and reading someone elses code is even harder. READMEs help others understand what you are doing with your code. It will also help others understand how they can contribute to your project. The technical world is lacking good documentation and this is a way to help improve that. Plus, if you can explain your code in plain english, that enables the growth of the technical community. 

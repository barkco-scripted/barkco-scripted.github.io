# Project Portfolio
An archive of resources and projects completed by Bark &amp; Co.'s ScriptEd Advanced Class 2016-2017.

## Getting Started


### 1. Fork this project

A fork is a copy of a repository. Forking a repository allows you to propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

### 2. Create a local clone of this fork

Right now, you have a fork of the project-portfolio repository, but you don't have the files in that repository on your computer. Let's create a clone of your fork locally on your computer.

1. On GitHub, navigate to your fork of the project-portfolio repository.
2. Under your repository name, click Clone or download and copy the clone URL for the repository.
3. Paste the url in the "Git URL" input under the "Hosted Workspaces" tab.

### 3. Configure Git to sync your fork with the original repository

When you fork a project in order to propose changes to the original repository, you can configure Git to pull changes from the original, or upstream, repository into the local clone of your fork.

1. From your project-portfolio repo, type `git remote add upstream`, and then paste the URL you copied in Step 2 and press Enter. It will look like this:

```
git remote add upstream https://github.com/barkco-scripted/project-portfolio.git
```

More detailed instructions can be found [here](https://help.github.com/articles/fork-a-repo/).

### 4. Create a new branch to add your changes

Whenever you begin work on a collaborative repository, it's important that you create a new branch. Not only is it proper git workflow, but it also keeps your changes organized and separated from the master branch so that you can easily submit and manage multiple pull requests for every task you complete.

1. In your project-portfolio directory, create a new branch with your name by typing `git branch "YOUR-NAME"` and press Enter.
3. Checkout your new branch, `git checkout YOUR-NAME`.
2. Go into the `students.html` and make the following edits: 
	* Change the heading from "Student #" to your name. 
	* Add a description about yourself, including your school and your favorite part about coding. Feel free to add any additional information you'd like, such as hobbies, where you live, etc. 
	* Add a picture of yourself (preferrable) or an avatar to the img `src`. Please add the image to the `images` folder and reference the local path, i.e. `images/my-picture.jpg`.
	* Update the `href` of the "View GitHub" button to your personal GitHub. Make sure to set `target="_blank"` so the url opens in a new tab. 


### 5. Create a pull request or _PR_

At last, you’re ready to propose changes into the project! This is the final step in producing a fork of someone else’s project, and arguably the most important. 

1. Add the files you've editing by typing `git add .`
2. Then commit the edited files by typing `git commit -m "YOUR-NAME edits"`.
3. Push your branch with your edits by typing `git push -u origin HEAD`.
4. Go to the [original project](https://github.com/barkco-scripted/project-portfolio) in GitHub and open a pull request.
5. Make sure `master` is selected as the base and select your forked copy branch as the branch to compare it to and create a pull request. 


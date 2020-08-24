# Git + GitHub Workshop Resources
Hello there :wave:  
These resources will help you get up and going with Git and GitHub.

## Installation
If you are a Windows user. Please download the following application to use the terminal in windows.
- [Git Bash](https://git-scm.com/downloads)

Or enable Windows SubSystem for Linux and follow the instructions for Linux systems.

For installing git on Ubuntu
```
$ sudo apt install git
```
After finishing the installation, run the following commands to configure the global user info for git on your computer.
```sh
$ git config --global user.name "Your github username"
```
```sh
$ git config --global user.email "Your email"
```

### Install a Favorite editor of your choice :computer:
You can install any of your favorite editor to start working on projects. I strongly recommend using VSCode, since it got a lot of Git integrations and plugins to help.

- [VSCode](https://code.visualstudio.com/)
- [Sublime Text](https://sublimetext.com)
- [Atom](https://atom.io)

## Resources :books:
Get started by watching the interview with [Linus Torwalds, The Mind Behind Linux](https://www.ted.com/talks/linus_torvalds_the_mind_behind_linux?language=en).

- [Daniel Shiffman's Git and GitHub tutorial](https://www.youtube.com/watch?v=BCQHnlnPusY), This is simply :heart:
- [Git Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
- [Git Additional Cheat Sheets](https://services.github.com/on-demand/resources/cheatsheets/)
- [Learn about Linux commands on CLI](https://www.youtube.com/watch?v=cBokz0LTizk) 
- [Udacity's Git and GitHub tutorial](https://in.udacity.com/course/how-to-use-git-and-github--ud775-india)
- [GitHub Training courses](https://lab.github.com)  from GitHub lab
- [GitHub Guides](https://guides.github.com/):The easiest way to get started with GitHub
- [Markdown Language Tutorial](https://www.youtube.com/watch?v=6A5EpqqDOdk)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- If you stuck on something, or want some handy git commands to get out of mess. Refer [Katie's Oh-Shit-Git!](https://ohshitgit.com/)
- [Learn Git With Git-Tower](https://www.git-tower.com/learn/): Covers some cool tutorials in both pdf and videos in addition to the different cheat sheets in different languages.
- Learn by doing:
  - [Learn Git branching](https://learngitbranching.js.org/)
  - [Visualizing Git](http://git-school.github.io/visualizing-git/): Enjoy an practice Git while visualising all what happens.

## Contributing to OpenSource :beginner:
- [FreeCodeCamp's curated list](https://github.com/freeCodeCamp/how-to-contribute-to-open-source) of resources to help new open sourcerers.
- Learn by making your first Pull Request at [GitMe](https://gitme.js.org)
- Find open issues you can work on at [issuehub](https://issuehub.io)
- Find project based on your interest at [up for grabs](https://up-for-grabs.net/#/)
- Submit 5 Pull Requests between October 1st and 31st to earn a free TShirt from [HacktoberFest](https://hacktoberfest.digitalocean.com)

## Extras for Linux fans :robot:
- Customize your terminal with [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh)
- Use [Bat](https://github.com/sharkdp/bat), Cat with wings
- [Vim Tutorials](https://www.youtube.com/watch?v=zIzdp3EciiY&vl=en) on how to get out of it
### Facing any issues?
Feel free to [open an issue](https://github.com/clubgamma/intro-git-github/issues/new) or contact the core team. We are glad to help you. :heart:

## Commands used during workshop :computer:	| :desktop_computer: :keyboard:
```
# To watch the status of your local repo
git status


# To add files in stage area
git add <file-name>
git add .


#  To save the changes permanently in history (by creating versions)
git commit -m <message>
git commit -am <message>


# To watch your commit history
git log


# To push your commited changes (or versions) to github
git remote add origin <link-of-your-project>
git push origin master


# To download whole code present on GitHub
git clone <link-of-project>


# To pull only changed code from GitHub
git pull origin


# To see all branches present in your project
git branch


# To create a new branch
git branch <branch-name>


# To delete branch safely
git branch -d <branch-name>


# To delete branch forcefully
git branch -D <branch-name>


# To rename branch
git branch -m <new-name>


# To change from one branch to another
git checkout <branch-name>


# To see the previous versions
git checkout <commit-index>


# To create a new branch and move to it
git checkout -b <new-branch-name>


# To merge branches
git checkout <final-branch-name>
git merge <branch-to-merge>


# To cancel merge process
git merge --abort
```


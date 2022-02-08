# A03

# Directions on Using Git and Github

### **Github** Overview/History
- **Github** is a version control system, meaning it's function is to help programmers to track and control revisions made to a software project.
- In addition to being a version control system, it also adds additional features that aren't avaliable on **Git** such as its user management feature.
- **Github** is a version of **Git** but is a service that is web-based (unlike **Git**) and has a graphical user interface. 
- **Github** was released by Chris Wanstrath, P. J. Hyett, Tom Preston-Werner and Scott Chacon in 2008.

### **Git** Overview/History
- Similar to **Github**, **Git** is a version control system, however it lacks many of the features that **Github** has.
- **Git** is a software that is installed locally on the user's system, and is accessed through the command-line.
- **Git** is supported by Linux and was released by Linus Torvalds (the creator of Linux) in 2005.

![This is an image of Git and Github](https://editor.analyticsvidhya.com/uploads/18288git.jpg)


### How to Use **Git/Github**
1. Get **Git/Github**

Follow this [link](https://github.com) to sign up for a **Github** account. You can also use this [link](https://git-scm.com/downloads) to install **Git**, which will help you use the system locally. 

When you first install **Git** you must set your user name and email address.
```
git config --global user.name "first last"
git config --global user.email "email address"
```
2. Create a **repository**

A **repository** is a collection of files for a project. To create a **repository** you need to open your terminal on your device (if you haven't done so already from the last step) and use the cd command with the place where you would like to have your **repository**.

For example, if I want a **repository** on my desktop, I would use the following command: 

```
cd ~/Desktop
```
To initialize the **repository** you use the following command: 
```
git init
```

(You can create a new **repository** on **Github** by loging in and going to your home page. You should then go to the "+" sign and click on "New repository") 

2. Add a file to the **repository**

To add a new file to the **repository** you can use the touch command with the file you want to add.

For example, if I want to add a project.txt file to the **repository** I would use the following:

```
touch project.txt
```

(You can also create new files on **Github** by going to your **repository** and clicking on the "Add file" button".) 

3. Add file to staging area

The **repository** contains three main sections: the working directory (holds files), the staging area (contains files that will be a part of the next commit), and the head (tracks **commits**). 

To add a file to the staging area use the git add command. 
  
```
git add <filename>
```

4. **Commit** 

To **commit** (changes to a file) use the **commit** command. You should include a message that gives a clear description of the changes that you've done to the project.

```
git commit -m "message"
```

(You can also **commit** on **Github** by clicking on the pencil icon, adding your changes to the file, and then click "**Commit** changes" on the bottom of the page") 

5. Make a **branch**

A **branch** is a feature in **git** that allows the user to seperate a part of the code from the main **branch** so the master **branch** can remain the same.

To create a new **branch** use the **branch** command. This command will make the requested **branch** and move you to that **branch**. 
```
git checkout -b <branchname>
```

6. **Push** **branch** to Github 

**Pushing** means you can make changes/updates to the **remote** (a **repository** that is not hosted locally such as **Github**) **branch** with local **commits**. To **push** changes to a new **branch** on **Github** use the following command:

```
git push origin <branchname>
```

7. **Pull** 

To get and **merge** changes from the **remote** **repository** or **Github** to the current **branch**, you can use the **pull** command.

```
git pull
```
8. **Merge**

**Merging** means the **commits** from the current **branch** are added to the main **branch**. To do this use the **merge** command as follows:

```
git merge <branchname>
```

Note: A **merge conflict** may occur when Git finds conflicting changes and does not know which changes to include and which to exclude. Consider visiting this [page](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line) to learn more about how you can resolve the issue if it ever comes up.

9. **Fetch**

By **fetching**, the user is able to download external files/**commits**, etc. from a **remote** **repository** to the local machine. To get the current history from the server and point the main **branch** to it, use this command:

```
git fetch origin
```

11. **Clone**

To **clone** or copy the **repository** from **Github** (web servers) to the user's machine, you can run the **clone** command as follows:

```
git clone /path/to/repository
```

To **clone** to a **remote** server, you can use this command: 

```
git clone username@host:/path/to/repository
```

# Directions on Using Webstorm
## Webstorm 
### Webstorm Overview/History 
- Webstorm is an integrated development environment (IDE) for multiple programming languages (including Java, JavaScript, Python, etc.). An IDE helps programmers code more efficiently and effectively with built-in tools such as a text editor, debugger, and code completion. 
- Webstorm was created by the software company JetBrains (founded in 2000).

### How to Use Webstorm**

1. Download Webstorm 

Use this [link](https://www.jetbrains.com/community/education/#students) to download Webstorm (student edition). Make sure to download and install the latest and correct version (for your machine). 

2. Open the app and create a project

After opening up Webstorm on your device, you will be brought to a welcome screen that gives you three options: "New Project", "Open", and "Get from VCS". Click on "New Project". Alternatively, you can select File > New > Project from the main menu. 

Choose Empty Project, pick the application folder for the project, and then click "Create".

3. Create a file in your project

In the context menu of the selection, cick "New" and pick the file type you want the added file to be.

![This image is from JetBrains and shows how to create a new file.](https://resources.jetbrains.com/help/img/idea/2021.3/ws_getting_started_create_new_file.png)

4. Get started coding 

You can now populate your files with code and run them using "Run" or the play button on the interface.

Good luck!

# Glossary

- **Branch**: a feature in git that allows the user to seperate a part of the code from the master (default or main) branch so the master branch can remain the same.
- **Clone**: a way to copy the repository from Github.com (web servers) to the user's machine.
- **Commit**: a change to a file.
- **Fetch**: downloads external files/commits, etc. from a remote repository to local machine.
- **GIT**: is a version control system that is a software and is installed locally on the user's system (accessed through the command-line).
- **Github**: is a version control system service that is web-based and has a graphical user interface.
- **Merge**: commits from the current branch are added to the main branch.
- **Merge Conflict**: happens when Git finds conflicting changes and does not know which changes to include and which to exclude.
- **Push**: changes/updates the remote branch with local commits.
- **Pull**: updates current branch with changes from remote server.
- **Remote**: a repository that is hosted remotely or not locally (most commonly via Github or internal server).
- **Repository**: is a collection of files for a project.


# References
1. [GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-git-and-github/)
2. [Github Documentation](https://docs.github.com/en)
3. [Hubspot](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
4. [Git](https://git-scm.com/docs/gittutorial)
5. [PhoenixNap](https://phoenixnap.com/kb/how-to-use-git)
6. [Jetbrains](https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html)
7. IS117 Powerpoint Slides

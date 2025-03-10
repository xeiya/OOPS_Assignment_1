# Question 1
#### List three major version control software for software engineering.

1. Git
2. SVN (Subdiversion)
3. Mercurial

# Question 2
#### What are the main advantages to using Git in your software development, and how is it useful for game developers.

<br>Git is a great management tool and offers superior performance with optimized committing, branching, and merging.
It also allows secure version management allowing the user to switch between versions and enables local branches for
switching between different branches for testing, staging and eventually release. With each branch having commit
modiications. It also allows users to work on projects anywhere anytime and is an open-source program<br>

# Question 3
### Define the following terms in relation to Git. Branch, Pull, Push, repository, merge

#### Branch - A pointer to a snapshot of your changes
#### Pull - To fetch and download content from a remote repository into the local repository to match that content
#### Push - Used to upload a local repository to a remote repository
#### Repository - A central storage location for managing and tracking changes in files and dictionaries
#### Merge - A way of putting two branches and merging it into one single branch

# Question 4
### If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.

- Tracking Changes - Keeping track of changes to see when it has been updated
- Collaboration - Being able to collaborate between multiple individuals or teams to improve the efficiency
- Auditing - To be able to view changes and reverse them when needed
- Accessibility - Can be accessed anywhere with an internet connection, making it easier for collaboration
- Conflict Resolution - The ability to resolve conflicts to make sure there is no overlap

# Question 5
### Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
- Meld
- Beyond Compare 3
- SourceGear Diff/Merge

# Question 6
### In a merged source code file, how does Git let you know there is a conflict?
When merging, git will produce a log with a list of commits that conflict brtween the merging branches

# Question 7
### What are the steps you can take to resolve Git conflicts?
You can delete the <<<<<<, =======, >>>>>>>> markers a make changes in the final merge. \
This will then show in the final merge

# Question 8
### What does git revert do, and how can you use it?
Git revert creates a new commit that is the opposite of an exisitng commit \
<br>To use enter
```
$ git revert
```

# Question 9
### What does git reset do, and how can you use it? 
Git reset takes the current branch and resets it to point somewhere else \
<br> To use enter
```
$ git reset
```
# Question 10
### What is the difference between git revert and git reset?
- git revert - Creates a new commit that undos the changes from a previous commit
- git reset - Changes the current branch back to the previous commit and rewrites the history of the other commits

# Question 11
### True or False: It is okay to commit broken code to the main branch.
False

# Question 12
### True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True

# Question 13
### Describe what is DevOps, how is it useful for game developers?
Devops is the combination of cultural philosophies, practices, and tools that 
increase and organizations ability to deliver application and services at high velocity

<br> This can be useful for gamedevelopers to have a development pipeline to follow and deliver
high quality games to the consumer

![Dev Ops png](./Images/devops.png)

# Question 14
### List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
- GitHub - Allows developers to build the software in a repository and collaborate with others remotely
- slack - Allows people to communicate efficently and get to know what is happening in the company
- docker - Docker is a software program which allows you to build, test and deploy application quickly

# Question 15
### What is CI/CD and how can it be used to automate the game development process?
CI/CD is the combined practices of continuous intergration and continuous delivery. 
<br>It can be automated by making it trigger everytime anyone in the team commits a change.
<br> It can be used in the development process for any updates for the game or bug fixes
<br> That need to be fixed
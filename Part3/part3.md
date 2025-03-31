# Git Manual

## Installing
### Requirements
* At least 1GB - 2GB's of RAM
* Minimum 50 MB of free disk space

## How to Install
### **Windows**
1. Navigate to the Git for Windows installer and download the latest version
2. Follow the instructions provided in the Git Setup wizard screen until the installation is complete
3. Open the windows command prompt(or **Git Bash** if you have it installed)
4. Type ```git version``` to vertify Git was installed

### **Mac**
1. Navigate to the macOS Git installer and download the latest version
2. Follow the instructions provided until the installation is complete

### **Linux**

**Debian/Ubantu**
1. Git packages are available using ```apt```
2. Navigat to your command prompt and run ```sudo apt-get update``` to make sure everything is up-to-date
3. To install Git, run the command: ```sudo apt-get install git-all```
4. Once the command output has been completed, you can verify by typing: ```git version```

**Fedora**
1. Git packages are available using ```dnf```
2. To install git, run the command: ```sudo dnf install git-all```
3. Once the command output has been completed, you can verify by typing: ```git version```

## How to Fix

## Windows
- Re-download the setup and viruse check it.
- Verify disk space and check for disk errors
- Temporarily disable your anti-virus during installation

## Mac
- Check if you have ther current version of git installed using the command
```
git --version
```

## **Linux**
Install aptitude first
```
sudo apt-get install aptitude
```
Then install git using the command
```
sudo aptitude install git
```

## Respitories and Branches
### Principles/Techniques with repositories
#### Secure your Repository
Secure your repository using GitHub's available security features to protect your code from vulnerabilties, 
unauthorized access and other potential security threats. Some features you should use for free public repositories are

- **Dependabot**: Notifies you of security vulnerabilities in your project's dependency network
- **Secret Scanning**: Scans your repository for secrets (such as API keys and tokens) and alerts you if a secret is found
- **Push Protection**: Prevents you (and your collaborators) from introducing secrets to the repository in the first place
- **Code scanning**: Identifies vulnerabilities and errors in your repository's code

Additionally, you might also consider:

- Adding a ```SECURITY.md``` file to your repository that provides instructions to your collaborators on how to report
security vulnerabilities found in your project
- Enabling "Private vulnerability reporting" for the repository, which lets collaborators to privately disclose vulnerabilites
found in your repository to you

#### Favor branching over forking
To streamline collaboration, work from a single repository. Creating pull requests between branches instead of between repositories.
Forking is best suited for accepting contributions from people that are unaffiliated with a project, such as open-source contributors

To maintain quality of important branches such as ```main```, while using a branching workflow, you can use protected branches
with required status checks and pull request reviews

### Principles/Techniques with branches
- **Adopt a consistent naming convention** - Establish a clear and consistent naming convention for your branches to help team members quickly identify the purpose of each branch

## Git Workflow
The Git Workflow revolves around maintaining the master code in a consistently
deployable condition, thereby enabling the seamless implementation of faster release cycles,
continuous integration and continuous delivery workflows

The type of branches that can be present in the Git Workflow are:

- **Main** - Houses the most recent stable code prepared for relase
- **Staging** - Where you prepare the application for release
- **Testing** - Where you test code and mechanics
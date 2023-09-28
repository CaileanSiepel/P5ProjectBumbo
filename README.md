# Startup Manual

### Editor 
For this project we will be using Visual Studio 2022. This is because it is used by Avans. U can divert from this choice. But it is recommended to use Visual Studio 2022.

### Cloning the project
To clone to project you can go to git commands and look for the [Git clone section](#git-clone).

### Database
For this project we are using a centralized database. The config will be done when the database is ready. This is so other team members do not have to config it themselves and we can all use the same data. The database will be hosted on a server. The database will be a SQL Server database.

# Version control
This part is dedicated to how we use version control and how we manage our codebase. We use git as our version control system and github as our remote repository.

### Github
We use github to store our codebase since its a familiar environment for all team members. Github also provides a good way to manage pull requests and gives a clear overview of the branches. 

### Pull requests
Pull requests are the best way to propose changes to the codebase. This allows a team member to review the changes and discuss any potential modifications before merging into the main branch. Code reviews will mainly be done by the project leader but occasionally by other team members.

### Branches
We use branches to seperate the different features and to keep the main branch clean. We use the following naming convention for branches: `feature/feature-name`. When a feature is finished and the code has been reviewed, the branch will be merged into the main branch.

### Git commands
Here are some useful git commands that we use on a daily basis.

#### Git clone
This command is used to clone a repository from github to your local machine. This command is only used once per repository.

```
git clone 'https/ssh link'(the link can be found on the github repository)
```

#### Git pull
This command is used to pull the latest changes from the remote repository to your local machine. This command is used every time you start working on the project.
```
git pull origin 'branch name'
```

#### Git checkout
This command is used to switch between branches. Or checking out a new branch.
```
git checkout 'branch name'
```
or to checkout a new branch
```
git checkout -b 'branch name'
```

#### Git add
This command is used to add files to the staging area. This command is used when you have made changes to a file and want to commit it. This can also be done through visual studio.
```
git add 'file name'
```
or to add all files
```
git add .
```

#### Git commit
This command is used to commit the changes to the local repository. This command is used when you have made changes to a file and want to commit it. This can also be done through visual studio.
```
git commit -m 'commit message'
```

#### Git push
This command is used to push the changes to the remote repository. This command is used when you have made changes to a file and want to push it to the remote repository. This can also be done through visual studio.
```
git push
```



## Coding guidelines
This part is dedicated for our coding conventions and guidelines. 
### Naming conventions

#### Local & private variables
Variables should be named in camelCase.

```
string firstName = "John";
private string firstName = "John";
```

#### Global variables
Global variables should be named in PascalCase.

```
public string FirstName = "John";
```

#### Classes
Classes should be named in PascalCase.

```
public class Person
{
	public string firstName { get; set; }
}
```

#### Methods & Method arguments
Methods should be named in PascalCase. Method argument should be named in camelCase.

```
public void PrintName(string firstName)
{
	Console.WriteLine(firstName);
}
```

### Code style

#### Indentation
We use tabs for indentation.

#### Brackets
We use the Allman style for brackets.

```
if (true)
{
	// Do something
}
```

#### Comments
We use the single line comment style.

```
// This is a comment
```

#### Spacing
We use spaces for spacing. 1 space per spacing.

```
int x = 1;
```

#### Operators
We use spaces around operators.

```
int x = 1 + 2;
```








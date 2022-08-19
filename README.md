# CI-CD-practice

### Introduction
Realised in the course of the Bosch AI Talent Accelerator Scholarship Bootcamp, Devops path.

####  System Requirements
* Establish SSH authentification and connection from AzureCLI to remote GitHub repo 
* Terminal Environment: Bash on AzureCLI
* Clone repo to AzureCLI

#### Steps

1. Download or prepare the folder containing the source files[^1][^2]
2. Create manually a new GitHub repo
3. Clone new repo to AzureCLI
4. Move the newly created  source files' folder to the newly created repo: to permit git commands to act upon/access this folder
5. Initialize, verify status, commit and push the folder to this GitHub repo.


#### Commands to prepare the environment

##### Step 1

Here we go creating the folder and files in *Bash* [^2][^3][^4]
````
mkdir starter_files

cd starter_files/

touch  hello.py Makefile  requirements.txt  test_hello.py

ls
````

##### Step 2

Here is a link to the created [repo](https://github.com/Benjamin-Ogunsade/CI-CD-practice)

##### Step 3

````
git clone git@github.com:Benjamin-Ogunsade/CI-CD-practice.git
````

<!-- Replace image with one that reveals not IDs and cut-to-size
![clone my devops github repository](https://user-images.githubusercontent.com/28298236/185532123-5c6f253f-677c-4d97-aee2-510a09e85160.jpg)
-->




##### Step 4

Navigate into the remote repo directory[^4][^5]:

````
cd CI-CD-practice/
ls
````
Move the created folder into the current directory[^4][^5]: 
````
mv     ~/azure-devops/starter_files/     .
ls
````

##### Step 5

It's time to commit (save changes) and push (upload/publish modifications)[^6]:
````
git init
git status
git add starter_files/
git status
git commit -m "Starter files first commit"
git status
git push
ls
````

:+1: O kaare Omooba 'Deposi n'Ilare n'le-ife


[^1]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
[^2]: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
[^3]: https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files
[^4]: https://www.earthdatascience.org/courses/intro-to-earth-data-science/open-reproducible-science/bash/bash-commands-to-manage-directories-files/#:~:text=Delete%20a%20Directory%20(%20rm%20%2Dr,%2Dr%20directory%2Dname%20).
[^5]: https://www.tomshardware.com/how-to/delete-directory-or-file-in-linux
[^6]: https://www.codegrepper.com/code-examples/shell/how+to+push+a+folder+to+github+repository
[^7]: https://stackoverflow.com/questions/5667106/how-to-delete-or-change-directory-of-a-cloned-git-repository-on-a-local-computer

# CI-CD-practice

### Introduction
Realised in the course of the Bosch AI Talent Accelerator Scholarship Bootcamp, Devops path.

####  System Requirements
* Establish SSH authentification and connection from AzureCLI to remote GitHub repo 
* Terminal Environment: Bash on AzureCLI
* Clone repo to AzureCLI

#### Steps

1. Download or prepare the folder containing the source files
2. Create manually a new GitHub repo
3. Clone new repo to AzureCLI
4. Move the newly created  source files' folder to the newly created repo: to permit git commands to act upon/access this folder
5. Initialize, verify status, commit and push the folder to this GitHub repo.


#### Commands to prepare the environment

##### Step 1

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

Navigate into the remote repo directory

````
cd CI-CD-practice/
````
Move the created folder into the current directory 
````
mv     ~/azure-devops/starter_files/     .
````

##### Step 5


````
git init
git status
git add starter_files/
git status
git commit -m "Starter files first commit"
git push
````

[^note]: :+1: O kaare Omooba 'Deposi n'Ilare n'le-ife

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

mkdir starter_files

cd starter_files/

touch  hello.py Makefile  requirements.txt  test_hello.py

ls

##### Step 3

<i> $ git clone git@github.com:Benjamin-Ogunsade/CI-CD-practice.git  </i>

##### Step 4

mv     ~/azure-devops/starter_files/     .

##### Step 5


````
git init
git status
git add starter_files/
git status
git commit -m "Starter files first commit"
git push
````


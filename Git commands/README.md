# Deployment the GitHub
### 1. Download and install the git
### 2. Open the git-bash.exe
### 3. Enter the following code in git-bash.exe
```
$ ssh $ ssh-keygen -t rsa -b 4096 -C "mail adress"
```
#### press enter until finish 

### 4. It will create a .ssh folder in C:\user\ and there are two keys data in this folder

#### id_rsa is a privity key \
#### id_rsa.pub is a public key

### 5. To GitHub site and go to setting page 

### 6. Select "SSH and GPG keys"

### 7. New SSH key 

### 8. Post the key to site from id_rsa.pub data

### 9. Open the Git Shell application(git-cmd.exe)

### 10. Enter the following code in git-cmd.exe
```
$ git config --global user.name "YOUR NAME"
```
```
$ git config --global user.email "YOUR EMAIL ADDRESS"
```
# Download the project from the GitHub site (SSH)
```
$ git clone git@github.com:"..." 
```
```
$ git clone  https://github.com/..
```
# Get the project status
```
$ git status
```
# Add the data to the GitHub (temporarily)
```
$ git add "file name".{file type}
```
# commit the data to the GitHub (temporarily)
```
$ git commit -m "describe"
```
# Push the data to the GitHub
```
$ git push
```
# Check the GitHub log
```
$ git log

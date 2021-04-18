# Git Command

###### Author:Raheem
###### Date: 2021.04.15

---

## Outline

* Windows
* Linux

---

## Deployment the GitHub

## Windows
    
* 1. Download and install Git
* 2. Open git-bash.exe
* 3. Enter the following code in git-bash.exe
 
    ```shell=
    $ ssh-keygen -t rsa -b 4096 -C "mail adress"
    ```
    * 
        * Press enter until finish

* 4. It will create a .ssh folder in the following path:
    * C:\user\ and there are two keys data in this folder
    
            id_rsa is a privity key
            id_rsa.pub is a public key

* 5. Go To GitHub website and go to the setting page
* 6. Select "SSH and GPG keys" option
* 7. New the SSH key
* 8. Post the key which from id_rsa.pub data to GitHub website
* 9. Open the Git Shell application(git-cmd.exe)
* 10. Enter the following code in git-cmd.exe

```shell=
$ git config --global user.name "YOUR NAME"
$ git config --global user.email "YOUR EMAIL ADDRESS"
```

* 
    * Success & finish

### Download the project from the GitHub site (SSH)

```shell=
$ git clone git@github.com:"..." 
$ git clone  https://github.com/..
```

* If your device is the first time to connect to GitHub, you will get the following message in Git CMD:

        The authenticity of host 'github.com (xxx.xxx.xxx.xxx)' can't be established.
        RSA key fingerprint is SHA256:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx.
        This key is not known by any other names
        Are you sure you want to continue connecting (yes/no/[fingerprint])?
    
    then just input "Yes" 
    
### Get the project status

```shell=
$ git status
```

### Check the GitHub log

```shell=
$ git log
```

### push the project to GitHub

* 1. Add the data 

    ```shell=
    $ git add "file name".{file type}
    ```
    
    * add all the data
    
    ```shell=
    $ git add *
    ```

* 2. commit the data 

    ```shell=
    $ git commit -m "describe"
    ```

*  3. Push the data to GitHub

    ```shell=
    $ git push
    ```

## Linux

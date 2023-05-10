# How to run this project

## 1. install git
 Git mainly helps to track the code change and it also used for code collabration.
 To install git do follow the commands given below:

```
sudo apt -y install git
```

## 2. Get the repo link
copy the repository link https://github.com/Sid123789/Help.git

## 3. Clone the repo 
When an repository is created in Github.com, it exists in remote repository. So by cloning your repository, it will create a local copy on your local system and sync that between two locations.
* To clone the repo:
    1. Navigate to the main page of the repository.
    2. From the list of files, click <>Code.
    3. Copy the URL for the repository.
        * To clone repo in HTTPs, click "HTTPS".
        * To clone repo using GitHub CLI, click GitHub CLI.
We used Github CLI to run our application.  

## 4. Run the code
### 4.1. Build the runtime (first time only)
To run the code in runtime, do the following instruction:
  1. lets create a shell script in the name of 'run.sh' and 
  2. Using the if condition run the another script named 'build.sh'. If the given variable a is true, then the build script will be executed, otherwise it will ended as shown below: 
        
        #!/bin/sh
            a=true
            if a  
            then
                echo "This script runs the build scripts"
                    source /venv/bin/activate
                    sh ./build.sh
                    python3 app.py   
            else
                echo "Oops something went wrong!"
            end
            fi

### 4.2. Run the code for exisiting runtime 
To run the code on existing run time. Run the build.sh script code. It holds the set of commands, to run the application. 
To run the activate code, we need venv. venv is nothing but an virtual environment that depends on the os we use in our application.

```
    sudo apt -y install python3 python3-pip python3-venv
```

__sdnawnd__ _lnxclwndkl_ 
1. afked
1. nkdnwokd

* jpijwpdow
* ndlanwmdpw
 
try `python3 start.py` scjspmdwmdl 
## Output 
![](figs/fornt_page.png)

# How to run this project

## __1. Install git__
 Git mainly helps to track the code change and it also used for code collabration.
 To install git do follow the commands given below:

```
sudo apt -y install git
```

## __2. Get the repo link__
copy the repository link https://github.com/Sid123789/Help.git

## __3. Clone the repo__
When an repository is created in Github.com, it exists in remote repository. So by cloning your repository, it will create a local copy on your local system and sync that between two locations.
* To clone the repo:
    1. Navigate to the main page of the repository.
    2. From the list of files, click <>Code.
    3. Copy the URL for the repository.
        * To clone repo in HTTPs, click "HTTPS".
        * To clone repo using GitHub CLI, click GitHub CLI.
We used Github CLI to run our application.  

## __4. Run the code__
### __4.1. Build the runtime (first time only)__
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

### __4.2. Run the code for exisiting runtime__ 
To run the code on existing run time. Run the build.sh script code. It holds the set of commands, to run the application. 
To run the activate code, we need venv. venv is nothing but an virtual environment that depends on the os we use in our application.

```
    sudo apt -y install python3 python3-pip python3-venv
```
_To get into the virtual environment use:_
```
python3 -m venv venv
```
_To activate the venv use:_
```
source /venv/bin/activate
```
_To install & upgrade pip in python3:_
```
python3 -m pip install --upgrade pip
```
_Finally install the requirements that supports to build the application_
```
pip install -r requirements.txt
```


## __5. Output__ 
![](figs/fornt_page.png)

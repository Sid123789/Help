# How to run this project

## __1. Install git__
 Git mainly helps to track the code change and it also used for code collabration.
 To install git do follow the commands given below:

```
sudo apt -y install git
```

## __2. Get the repo link__
Copy the repository link https://github.com/Sid123789/Help.git

## __3. Clone the repo__
When an repository is created in Github.com, it exists in remote repository. So by cloning your repository, it will create a local copy on your local system and sync that between two locations.
* To clone the repo:
 ```
 git clone https://github.com/Sid123789/Help.git
```
We used Github CLI to run our application.  

## __4. Run the code__
### __4.1. Build the runtime (first time only)__
To run the code in runtime, do the following instruction:
  1. To run the activate code, we need venv, python3 and pip.
        *  venv is nothing but an virtual environment that depends on the os we use in our application.
        *  python3 is an software where our application is developed using it.
        *  pip is an package installer in python, that helps to install all the dependencies to run an application.

   ```
    sudo apt -y install python3 python3-pip python3-venv
   ```
 
  5. To install & upgrade pip in python3:_
   ```
    python3 -m pip install --upgrade pip
   ```
  6. Finally install the requirements that supports to build the application_
   ```
    pip install -r requirements.txt
   ```

### __4.2. Run the code for exisiting runtime__ 
To run the code on existing run time. After installing all the dependencies that application needed to run a python file. Run the below command:
   ```
    cd Help
    python3 -m venv venv
    source venv/bin/activate
    python3 app.py
   ```
  Here 'app.py' denotes the python file where we have set of codes to run the application.


## __5. Output__ 
![](figs/fornt_page.png)

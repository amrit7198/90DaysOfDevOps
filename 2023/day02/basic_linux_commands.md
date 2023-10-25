## Basic linux commands

### Listing commands
```ls option_flag arguments ```--> list the sub directories and files avaiable in the present directory

Examples:

- ``` ls -l ```--> list the files and directories in long list format with extra information
 ![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/849b4f34-9536-40ef-a1e6-9e034cd95f37)

- ```ls -a ```--> list all including hidden files and directory
  ![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/7417a377-2998-4b18-a60d-b2f0b94e18c4)

- ```ls *.sh``` --> list all the files having .sh extension.
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/11671867-065a-4aae-8ba2-c041c6fe3c43)

- ```ls -i ``` --> list the files and directories with index numbers inodes
  ![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/75cdfb29-941a-4f24-9ac7-625624059110)

- ``` ls -d */``` --> list only directories.(we can also specify a pattern)
  ![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/bea2c030-2583-47da-a4d4-742ac180b16c)


### Directoy commands
- ```pwd``` --> print work directory. Gives the present working directory.
  ![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/ef8737a8-5c0f-471d-bb5d-56990c46b8f9)


- ```cd path_to_directory``` --> change directory to the provided path
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/2e44d40d-5c76-4fb0-81f9-2b6feb89b8aa)

- ```cd ~ ``` or just  ```cd ``` --> change directory to the home directory
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/e2b26aa4-8323-4a50-a206-31e9b21e8144)

- ``` cd - ``` --> Go to the last working directory.
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/6da3222c-3894-45c4-afa0-75bc961e1d5e)

- ``` cd ..``` --> change directory to one step back.
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/bf0473b2-4fb3-4b08-bf94-d6a0c633d926)

- ``` cd ../..``` --> Change directory to 2 levels back.
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/c8a84899-6494-4597-9e9b-f7d7a8a4c770)

- ``` mkdir  directoryName``` --> to make a directory in a specific location
![image](https://github.com/amrit7198/90DaysOfDevOps/assets/36197073/38df20f6-5627-4d91-9823-6a41e5c2d5b5)

Examples:
```
mkdir newFolder              # make a new folder 'newFolder'

mkdir .NewFolder              # make a hidden directory (also . before a file to make it hidden)

mkdir A B C D                  #make multiple directories at the same time

mkdir /home/user/Mydirectory   # make a new folder in a specific location

mkdir -p  A/B/C/D              # make a nested directory
```

# Make permanant shortcut

##### 1- Open gpush file

##### 2- Copy the script (exclude the 1st line)

```
read -p "commit message: " m
git add .
git commit -m "$m"
git push

```

##### 3- Open terminal

##### 4- Go to /root directory

by running cd command

```
cd
```
##### 5- Open .bashrc file in editor (ex: vi)

```
vi .bashrc
```
##### 6- Go to the end of the file

##### 7- Add a function (we will name it gpush)

##### 8- Paste the script inside the function

```
gpush()
{
	#script
}
```
##### 9- Save and exit file (:wq)

##### 10- Restart terminal

or run 
```
source .bashrc
```
New command syntax:

open repo directory and run 

```
gpush
```

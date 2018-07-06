# linux-commands
all linux-commands

### 1. Transfer files/folder to remote srever

Type this while you are at the directory of your local computer

```
scp -r localfile user@remote_server:/remote_home/remote_directory
ex: scp -i  vasukeypair.pem newphoto/ma.jpg  ubuntu@ec2-X.X.X.X.compute-1.amazonaws.com:~/dog-project/ 
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
1. http://searchenterpriselinux.techtarget.com/tutorial/77-useful-Linux-commands-and-utilities

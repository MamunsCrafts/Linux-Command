# Linux  Essential Commands 

## Package Management

### Update Packages List
```
sudo apt update
```

### Upgrade Packages 
```
sudo apt upgrade
```

### Install debian packages

```
sudo dpkg -i [file.deb]
```


### Search Packages 

```
dpkg -l | grep [file_name]
```
### UnInstall debian packages

```
sudo apt-get remove --purge [package-name]

```


## Basic Navigation and File Operations
### Print working directory

``` pwd
```

### List directory contents
```
ls

```

### List directory contents with hidden files
```
ls -la
```
### Change directory
```
cd
```

### Create New Directory 
```
mkdir
```
### Remove File 
```
rm [filename]
```

### Copy files or directories
```
cp [source] [destinaiton]
```
### Move file or directories
```
mv [source] [destination]
```

## File Editing

### Open file and nano editor
```
nano [file_name]
```

### Display Content
```
cat [file_name]
```
### Create New Empty File
```
touch [file-name]
```

## System Monitoring and process control

### Display running processes and resource usage
```
top
```
### Enhance version of top .(Needs to be installed)
```
htop
```
### List of all running processes
```
ps aux
```
### Terminate a process
```
kill [process-id]
```
### Show disk usage

``` 
df -h
```
### Show memory usage
```
free -h
```




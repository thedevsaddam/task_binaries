# Task binary

Command line task management tool

## Download

| OS      	| x86                                                                                      	| x86_64                                                                                      	|
|---------	|------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|
| Mac     	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/mac_x86.zip)     	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/mac_x86_64.zip)     	|
| Linux   	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/linux_x86.zip)   	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/linux_x86_64.zip)   	|
| FreeBSD 	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/freebsd_x86.zip) 	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/freebsd_x86_64.zip) 	|
| Windows 	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/windows_x86.zip) 	| [Download](https://github.com/thedevsaddam/task_binaries/blob/master/v1/windows_x86_64.zip) 	|


### Installation
Mac/Linux download the binary and unzip it then follow the instruction below
```bash
$ cp task /usr/local/bin/task
$ sudo chmod +x /usr/local/bin/task
```
**For windows download the binary and set environment variable so that you can access the binary from terminal**

### Custom File Path
If you are interested to sync the task in dropbox/google drive, you can set a custom path. To set a custom path
 open your `.bashrc` or `.bash_profile` and add this line `export TASK_DB_FILE_PATH=Your file path`
 
 Example File path
 ```bash
export TASK_DB_FILE_PATH=/Users/thedevsaddam/Dropbox  # default file name will be .task.json
export TASK_DB_FILE_PATH=/Users/thedevsaddam/mytasks.json
```

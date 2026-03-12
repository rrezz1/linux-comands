# Section 10

## 37)

automation

**cron**
>is a time-based job scheduler that automates the execution of repetitive tasks, commands, or scripts at specified intervals

**cron**
>an automated task in Linux/Unix-like operating systems that is scheduled to run periodically at specific dates and times without manual intervention

**cron**
>the command used to create, edit, and manage a user's scheduled tasks

### **crontab -l**
>i list kejt crontabs

### **crontab -e** (to edit)
>fshi kejt edhe bone paste

> ```
> * * * * * <command to execute>
> # | | | | |
> # | | | | day of the week (0–6) (Sunday to Saturday; 7 is also Sunday on some systems)
> # | | | month (1–12)
> # | | day of the month (1–31)
> # | hour (0–23)
> # minute (0–59)
> shto
> * * * * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt (path ku don me ru)
>  ```

### **qdo or**
>  ```
> 0 * * * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```

### **qdo 7:15**
>  ```
> 15 7 * * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```

### **qdo minut n 6**
>  ```
> * 6 * * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```

### **me 21:13 qdo met 10 qdo muj**
>  ```
> 13 21 10 * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```


### **me 21:13 qdo met 10 , janar**
>  ```
> 13 21 10 1 * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```


### **me 21:13 qdo dille**
>  ```
> 13 21 * * 0 echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```


### **me 21:10,21:20,21:30**
>  ```
> 10,20,30 21 * * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```


### **me 21 every 10 minuts**
>  ```
> */10 * * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```


### **qdo 10 minuta prej 7 deri 9**
>  ```
> */10 8-9 * * echo "Hello" >> /c/Users/User/testLinuxComands/file.txt  
>  ```

### **crontab -r**
>to remove

### **ushtro**
>[https://crontab.guru/](https://crontab.guru/)

## 38)

### **cd /lib/systemd/system**
>shko per me shtu ni service
>
>e shtojna
>
>sudeo nano ensure-log-folder-exists.service
>
>  ```
>  [Unit]
>  Description=Create file log on boot
>  After=multi-user.target
>  
>  [Service]
>  ExecStart = mkdir /home/rrezz/logs
>  User=rrezz
>  
>  [Install]
>  WantedBy=multi-user.target
> ```

### **sudo systemctl list-unit-files**
>i shohim kejt files qe jan enable/disable

### **sudo systemctl list-unit-files | grep ensure**
>kallzon tonen

### **sudo systemctl enable ensure....** (name)
>per me bo enable

>### **sudo systemctl disable ensure....** (name)
>per me bo disable

>### **sudo systemctl stop ensure....** (name)
>per me bo stop

>### **sudo systemctl start ensure....** (name)
>per me bo start

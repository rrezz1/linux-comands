# Section 10

## 37)

automation

**cron**
>is a time-based job scheduler that automates the execution of repetitive tasks, commands, or scripts at specified intervals

**cron**
>an automated task in Linux/Unix-like operating systems that is scheduled to run periodically at specific dates and times without manual intervention

**cron**
>the command used to create, edit, and manage a user's scheduled tasks

###**crontab -l**
>i list kejt crontabs

###**crontab -e**
>fshi kejt edhe bone paste

> ```
> * * * * * <command to execute>
> # | | | | |
> # | | | | day of the week (0–6) (Sunday to Saturday; 7 is also Sunday on some systems)
> # | | | month (1–12)
> # | | day of the month (1–31)
> # | hour (0–23)
> # minute (0–59)
> ```

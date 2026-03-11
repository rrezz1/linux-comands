# Section 5

## 19)

*permisions qysh me i add prej userit ton , me i change , edit....*

### **source.list**

>kthemi fillim kejt cd

>cd /etc/apt

>nese provojna me move mv source.list abc -> permmision denied

>dmth nese jena folderat qe sjan prej home/useri , mujna me write naj file amo JO me ndrro permission 

## 20)

*run a command with admin privilege -> sudo*

### **sudo**

>kejve komandav ja shtojna sudo edhe bojn

>duhet pw i userit 

*KUJDES KUR E PERDOR SUDO*


## 21)

*Understend file owner and permission*

### **list -l**

>t dhana mashum, owner i filev kush o

### **list -l ~**

>t dhanat e Users/User

### **groups**

>secili user ka root grup qe o i njejt me user name


### **fillon me d kur o dir, me - kur o file**

drwxr-xr-x

>r-> read

>w-> write

>x-> execute

dmth mndahen me gr edhe secili gr psh te **drwxr-xr-x** mun me:


>drwxr -> read, writem, execute

>xr -> execute, read

>x -> execute



## 22)

*Change a file's OWNER* 

kur krijojna file me sudo (jo user ton), owner o root, na mujna veq me read 

### **ls -s fileName.txt**
>t dhonat per qet file

### **chown** (change the owner)
>man chown per dokumentim


### **sudo chown rrez fileName** (rrezz->userName)

>tash u ndrry ovner so root po rrez

> tash qeti file ju qasim pa sudo

>AMOOOOOOO nuk mujna me delete se sjena onwer i dir veq i file, sooo we need sudo


## 23)

*Change a file's PERMISSIONS*

drwxr-xr-x root root -> e para o Owner , e dyta o Grupi (spe di a kom shkru)

### **chmod** (change mode)
>me i modify permission


### **chmod u+w sciptName.bash** (ose u-w) 
>per me shtu ose me hek per userin n ket rast write 



### **chmod g+w sciptName.bash** (ose g-w) 
>e njejta veq kjo per grup


### **chmod o+w sciptName.bash** (ose o-w) 
>e njejta veq kjo per other

### **chmod w sciptName.bash** (ose -w) 
>e bon qet permission per kejt

### **chmod ugo+w sciptName.bash** (ose ugo-w) 
>per 2 psh 


USHTRIM

*User Ed munet me read, write, execute*

*Grupi mun me read edhe execute*

*others mujn veq me execute*

>chmod u+rwe scriptName.bash

>chmod g+rwe scriptName.bash


qetu mujna edhe

>read  4

>write 2

>execute 1

>rwe 7

>chmod 751 scriptName.bash

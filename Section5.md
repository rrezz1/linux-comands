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



## 21)

*Change a file's OWNER* (letsgooooooooo)

kur krijojna file me sudo (jo user ton), owner o root, na mujna veq me read 

### **ls -s fileName.txt**
>t dhonat per qet file

### **chown** (change the owner)
>man chown per dokumentim


### **sudo chown rrez fileName** (rrezz->userName)

>tash u ndrry ovner so root po rrez

> tash qeti file ju qasim pa sudo


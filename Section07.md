# Section 7

## 27)

find allow u to list everything 

###  **find .**
>i kthen gjithqka n folldera
>
>edhe file tyne

###  **find /usr/bin**
>i kthen gjithqka qe ka n specific path

###  **find ~ -name "my*"**
>kthen kejt file qe fillojn me my edhe kan tekst tjt...

###  **find /usr/bin -name "my*"**
>kthen kejt file qe nisin me my te pathi /usr/bin

###  **find . -maxdepth 1**
>qekjo nuk lyp ner qat path, dmth veq 1 e gjen nuk ja mer child

###  **find . -maxdepth 2**
>ja mer 1 child

###  **find . -maxdepth 2 -name "my*"**
>per filet qa fillojn me my, edhe childs i kthen qa fillojn me my

## 28)

# tash ktu e kena qysh me i find line te ni text

###  **grep "what u need" fileName.txt**
>qetu i kthen kejt lines qa e permbajn "what u need" te file fileName.txt

###  **grep -i "what" fileName.txt**
>e njejta veq me -i e ignore the case, i kthen kejt edhe me What edhe what

###  **grep "^what" fileName.txt**
>i kthen kejt qa fillojn fillim me what

## 29)

paths jan super useful n terminal se na nimojn me i kombinu komandat

**|** (pipe)

###  **ls -l | wc**
>i bon count lines

###  **ls -l | wc**
>i bon count lines


###  **find /usr/bin | grep dir**
>i gjen kejt qa e kan dir


###  **find /usr/bin | grep dir | wc**
>i gjen kejt qa e kan dir edhe kthen count n tyne

###  **grep "a" fileName.txt | wc**
>i kthen lines qe kan a
>
>e para i kthen lines

njejt 

###  **cat fileName.txt | grep "a" | wc**
>cat i print lines qe kan a

###  **cat fileName.txt | grep"name" > newFileName.txt**
>ii merr kejt qa kan lines qe kan fjalen name edhe i qet te newFileName.txt

###  **cat /etc/apt/sources.list | grep"^deb"**
>kthen kejt lines prej qati path qa nisin me fjalen feb
 
###  **cat /etc/apt/sources.list | grep "^deb" > ~/dirName/rewrite.txt**
>i revrite lines prej sources.list qe fillojn me deb te rewrite.txt

##  30)

shortcuots

###  **Tab**
> e fill emrin 

###  **UP/DOWN ARROWS**
>komandat qe i kena shkru

###  **CTRL + SHIFT + C**
>copy n terminal

###  **CTRL + SHIFT + V**
>paste n terminal


###  **CTRL + C**
>stop any process qe o tu bo

###  **CTRL + A**
>t qet fillim line t komandes

###  **CTRL + E**
>t qet fund line t komandes

###  **CTRL + U**
>kur je midis line
>fshin kejt qa ka perpara prej pozites qe je

###  **CTRL + K**
>kur je midis line
>fshin kejt qa ka permas prej pozites qe je

###  **CTRL + R**
>e bon search komanden qa ke use, amo fjalen e par n qata bazohet

###  **CTRL + SHIFT + T**
>e qel i tab t ri n qat terminal

###  **tmux**
>qel terminal mrena terminalit

###  **sudo apt install terminator**
>per me instalu terminatorin

###  **CTRL + SHIFT + O**
>split horizontal

###  **CTRL + SHIFT + E**
>split vertical

###  **CTRL + SHIFT + X**
>to add and remove a specific terminal in full screen

###  **ALT + L**
>e qel layout qe e kena ru

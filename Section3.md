# Section 3

*Ne LINUX gjithqka eshte file, edhe folderi eshte file specifik qe ka file mrena tij*


## 11)

**touch fileName** 
>krijon file , fileName emri
>ne windows duhet per txt me bo fileName.txt

**touch file Name**
>krijon edhe file edhe name(2 veqmas) 


**rm fileName**(remove)
>e bon file remove

>mujna psh rm fileName Test/fileName, i bon remove 2at

>munet mu perdor per mashum p.sh rm file1 file2

**man commandName**(manual)
>nese pash man rm , na tregon per komanden rm qka sakt bon

**mv fileName myFolder/fileName**(move)
>argumenti 1 fileName osht emri file

>argumenti 2 myFolder/fileName osht veni ku po don me move

**mv fileName fileChanedName**(move + rename)
>argumenti 1 fileName osht emri file

>argumenti 2 fileChanedName osht veni ku po don me move(qe i bjen o vendin e njejt n qet rast) edhe me ja ndrru emrin, mun psh /home/test/fileChanedName


**cp fileName newFileName**(copy)
>argumenti 1 fileName osht emri file qe bohet copy

>argumenti 2 fileName osht emri file qe bohet paste, mun psh /home/test/newFileName

## 12)

**mkdir dirName**(make directory)
>perdoret per me kriju directory(folder)

**rm -r dirName**(remove directory)
>perdoret per me remove directory

**mkdir -p dirName**
>mujna me i kriju njo pas njo psh mkdir dir1/dir2/dir3

**mv dirName toDirName**
>per me move dir njejt si file 

>mujna te toDirName me bo psh Desktop/toDirName , per me rename ndrro toDirName

## 13)

**wget linkText**
>get something from the web

**cat fileName.txt**(concatenate)
>e print kejt file 

**less fileName.txt**
>munesh file me kqyr, up and down arrow to scroll 

>for exit press Q


**wc fileName.txt**
>te dhena per file, ben return:
>lines, words, size of file(amount/100 = value kb)

## 14)

**echo "hello world"**
>ben print hello world ne terminal


**echo "hello world" > fileName.txt**
>e ben print tekstin ne file

>nese ka tekst tjt e fshin veq hello world e len

>mujna fileName.text me bo njo qa sekziston edhe e krijoj + e shkrun

**echo "hello world" >> fileName.txt**
>e ben print tekstin ne file, nuk i fshin t dhanat tjera veq i shton


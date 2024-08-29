## Objetivo

The password for the next level is stored in the file **data.txt** next to the word **millionth** 

  

## Datos de acceso al nivel

user: bandit7

pass: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
## Solución

`bandit7@bandit:~$ ls`

`data.txt`

`bandit7@bandit:~$ ls -la`

`total 4108`

`drwxr-xr-x  2 root    root       4096 Jul 17 15:57 .`

`drwxr-xr-x 70 root    root       4096 Jul 17 15:58 ..`

`-rw-r--r--  1 root    root        220 Mar 31 08:41 .bash_logout`

`-rw-r--r--  1 root    root       3771 Mar 31 08:41 .bashrc`

`-rw-r-----  1 bandit8 bandit7 4184396 Jul 17 15:57 data.txt`

`-rw-r--r--  1 root    root        807 Mar 31 08:41 .profile`

`bandit7@bandit:~$ wc data.txt`

  `98567  197133 4184396 data.txt`

`bandit7@bandit:~$ wc -l data.txt`

`98567 data.txt`

`bandit7@bandit:~$ grep millionth data.txt`

`millionth       dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc`

`bandit7@bandit:~$ grep -n millionth data.txt`

`86483:millionth dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc`

`bandit7@bandit:~$`

## Notas Adicionales

`wc -l/ cuenta las lineas que tiene un archivo de texto`

`grep -n millionth data.txt`

    el comando grep permite filtrar las lineas de un archivo en base a un patron

    -n indica a grep que muestre el numero de linea





### Referencias 



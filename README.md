# overthewire

## bandit

### level 0

```
ssh bandit0@bandit.labs.overthewire.org -p 2220

```

> password = bandit0


### level 0 -> 1

ssh bandit1@bandit.labs.overthewire.org -p 2220

>

```

ls
cat readme

```

> NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL



### level 1 -> 2

> ssh bandit2@bandit.labs.overthewire.org -p 2220


> NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL


```

ls   # to list the files 

mkdir /tmp/newdir  # write permisiionis disabled in default home/user directry

cp - /tmp/newdir #copy the - file containg passwrd so that we can change it name

cd /tmp/newdir 

mv - file

cat file

```

> rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

### level 3

> ssh bandit2@bandit.labs.overthewire.org -p 2220

> rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

```
ls

cat spaces\ in\ this\ filename

```

> aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG


### level 4

> ssh bandit3@bandit.labs.overthewire.org -p 2220

> aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

```

cd inhere/

ls -a

cat .hidd*


```

> 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe


### level 5

> ssh bandit4@bandit.labs.overthewire.org -p 2220

> 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe


```

ls 

cd inhere

ls

```
> -file07 # is the file containing the password

``` 

cat ./-file07

``` 

> lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

### level 6   ( 5 -> 6 )

> ssh bandit5@bandit.labs.overthewire.org -p 2220

> lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

*hint human-readable
1033 bytes in size
not executable*


```
ls

cd inhere/

ls maybehere*/**

ls maybehere*/** -al # to check human readable

mkdir /tmp/jjjj

cp -r * /tmp/jjjj

cd /tmp/jjjj

find -executable

delete all the files showing


```
or 

```

ls */.* -al -S | grep 1033

```

> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU


### level 7  ( 6 -> 7 )

> ssh bandit6@bandit.labs.overthewire.org -p 2220

> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
 
 **Tip** 
 
    owned by user bandit7
    owned by group bandit6
    33 bytes in size


```
$ ls -a

.  ..  .bash_logout  .bashrc  .profile

$ cd ..
$ls -l
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit0
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit1
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit10
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit11
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit12
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit13
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:18 bandit14
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit15
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit16
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:18 bandit17
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit18
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit19
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit2
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit20
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit21
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit22
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit23
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit24
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit25
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:18 bandit26
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit27
4 drwxr-x--- 3 bandit27-git bandit27-git 4096 Jan 11 19:18 bandit27-git
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit28
4 drwxr-x--- 3 bandit28-git bandit28-git 4096 Jan 11 19:18 bandit28-git
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit29
4 drwxr-x--- 3 bandit29-git bandit29-git 4096 Jan 11 19:18 bandit29-git
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 bandit3
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit30
4 drwxr-x--- 3 bandit30-git bandit30-git 4096 Jan 11 19:18 bandit30-git
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit31
4 drwxr-x--- 3 bandit31-git bandit31-git 4096 Jan 11 19:18 bandit31-git
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit32
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit33
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 bandit4
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 bandit5
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit6
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 bandit7
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 bandit8
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:18 bandit9
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 drifter0
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter1
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter10
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter12
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter13
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter14
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 drifter15
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter2
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter3
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter4
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter5
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 drifter6
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter7
4 drwxr-xr-x 3 root         root         4096 Jan 11 19:19 drifter8
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 drifter9
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 formulaone0
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 formulaone1
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 formulaone2
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 formulaone3
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 formulaone5
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 formulaone6
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton1
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton2
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton3
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton4
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton5
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton6
4 drwxr-xr-x 2 root         root         4096 Jan 11 19:19 krypton7
4 drwxr-x--- 3 ubuntu       ubuntu       4096 Jan 11 19:13 ubuntu

$ cd bandit7 
$ ls
data.txt
$ ls -als
total 4108
   4 drwxr-xr-x  2 root    root       4096 Jan 11 19:19 .
   4 drwxr-xr-x 70 root    root       4096 Jan 11 19:19 ..
   4 -rw-r--r--  1 root    root        220 Jan  6  2022 .bash_logout
   4 -rw-r--r--  1 root    root       3771 Jan  6  2022 .bashrc
4088 -rw-r-----  1 bandit8 bandit7 4184396 Jan 11 19:19 data.txt
   4 -rw-r--r--  1 root    root        807 Jan  6  2022 .profile
   
   















### level 8 

> 




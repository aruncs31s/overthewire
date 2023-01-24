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

### level 6   ( 5 - > 6 )

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

```

ls */.* -al -S | grep 1033

```

> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU


### level 7  ( 6 -> 7 )

> ssh bandit6@bandit.labs.overthewire.org -p 2220

> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

```








### level 8 

> 




# BANDIT - OVER THE WIRE


## [Bandit Level 0](https://overthewire.org/wargames/bandit/bandit0.html)

```
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

> ### Key : bandit0


## [Bandit Level 0 -> 1](https://overthewire.org/wargames/bandit/bandit1.html)

```
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
logout
```

> ### Key : NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL


## [Bandit Level 1 -> 2](https://overthewire.org/wargames/bandit/bandit2.html)

```
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./-
logout
```

> ### Key : rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi


## [Bandit Level 2 -> 3](https://overthewire.org/wargames/bandit/bandit3.html)

```
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cat spaces\ in\ this\ filename
logout
```

> ### Key : aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG


## [Bandit Level 3 -> 4](https://overthewire.org/wargames/bandit/bandit4.html)

```
ssh bandit3@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls -a
cat .\.hidden
logout
```

> ### Key : 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe


## [Bandit Level 4 -> 5](https://overthewire.org/wargames/bandit/bandit5.html)

```
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls
file -i ./\
*
cat ./\-file07
logout
```

> ### Key : lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR


## [Bandit Level 5 -> 6](https://overthewire.org/wargames/bandit/bandit6.html)

```
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd inhere
find -size 1033c ! -executable
find -type f -size 1033c ! -executable -exec file {} + 
cd maybehere07
ls -a
cat \.file2
logout
```

> ### Key : P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU


## [Bandit Level 6 -> 7](https://overthewire.org/wargames/bandit/bandit7.html)

```
ssh bandit6@bandit.labs.overthewire.org -p 2220
ls
cd /
find -size 33c -user bandit7 -group bandit6
cat /var/lib/dpkg/info/bandit7\.password
logout
```

> ### Key : z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

## [Bandit Level 7 -> 8](https://overthewire.org/wargames/bandit/bandit8.html)

```
ssh bandit7@bandit.labs.overthewire.org -p 2220
ls
cat data.txt
grep -i millionth data.txt
logout
```

> ### Key : TESKZC0XvTetK0S9xNwm25STk5iWrBvP


## [Bandit Level 8 -> 9](https://overthewire.org/wargames/bandit/bandit9.html)

```
ssh bandit8@bandit.labs.overthewire.org -p 2220
ls
sort data.txt | uniq -u
logout
```

> ### Key : EN632PlfYiZbn3PhVK3XOGSlNInNE00t


## [Bandit Level 9 -> 10](https://overthewire.org/wargames/bandit/bandit10.html)

```
ssh bandit9@bandit.labs.overthewire.org -p 2220
ls
strings data.txt | grep ==
logout
```

> ### Key : G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s


## [Bandit Level 10 -> 11](https://overthewire.org/wargames/bandit/bandit11.html)

```
ssh bandit10@bandit.labs.overthewire.org -p 2220
ls
base64 -d data.txt
logout
```

> ### Key : 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM


## [Bandit Level 11 -> 12](https://overthewire.org/wargames/bandit/bandit12.html)

```
ssh bandit11@bandit.labs.overthewire.org -p 2220
ls
cat data.txt | tr [N-ZA-M] [A-Z] | tr [a-z] [n-za-m]
logout
```

> ### Key : JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv


### [Bandit Level 12 -> 13](https://overthewire.org/wargames/bandit/bandit13.html)

```
ssh bandit12@bandit.labs.overthewire.org -p 2220
ls
file data.txt
mkdir /tmp/[your_name]
cp data.txt /tmp/[your_name]/data.txt
cd /tmp/amrit
xxd -r data.txt | mv new
mv new new.gz
gzip -d new.gz
file new
bzip2 -d new
file new.out
mv new.out new.gz
gzip -d new.gz
file new
mv new new.tar
tar xvf new.tar
file data5.bin
tar xvf data5.bin
file data6.bin
mv data6.bin data6.bz2
bzip2 -d data6.bz2
tar xvf data6
file data8.bin
mv data8.bin data8.gz
file data8
cat data8
logout
```

> ### Key : wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
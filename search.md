# Linux Basic Commands
## Search 

**Author:** ApostolR1 
**Date:** 2026-04-19

---

## 1. find / -name "*.txt" 2>/dev/null

### Description 
The `find / -name "*.txt" 2>/dev/null` command need for search, **ignoring errors**

### Command
```bash 
find / -name "*.txt" 2>/dev/null 

```
![typing command in the terminal](find-name.png)

## 2. grep "text" file.txt

### Descriotion 
The `grep "text" file.txt` command need for find lines of text in a file

### Command
```bash
grep "text" file.txt

```
![typing command in the terminal](grep.png)

## 3. grep -r "text" /folder/

### Description 
The `grep -r "text" /folder'` command need for find lines for text in a file **recursively**

### Command
```bash
grep -r "text" /folder/

```
![typing command in the terminal](grep-r.png)

## 4. which python

### Description 
The `which python" command shows where the python **executable** file is located

### Command 
```bash
which python

```
![typing command in the terminal](which.png) 

## 5. whereis python

### Description 
The `whereis pytnon` command for search python files **(bin,source code,man)**

### Command 
```bash
whereis python 

```
![typing command in the terminal](whereis.png)
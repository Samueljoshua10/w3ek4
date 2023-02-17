# CIT 352: Chapter 4

<!-- TODO -->
```
Samuel
```

## Project 4-1

### Step 7

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(16).png

## Project 4-2

### Step 11

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(17).png

## Project 4-3

### Step 16

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(18).png

## Project 4-4

### Step 10

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(19).png

## Project 4-5

### Step 10

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(20).png

## Project 4-6

### Step 7

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(21).png

## Project 4-7

### Step 10

Why were you able to succeed in `cd /foruser1`?

<!-- TODO -->
```It is just the execute permission on the directory that gives you permissions to do that command.
```

Why were you able to list the content of `/foruser1` direction?

<!-- TODO -->
```
 it is the read permission on that directory that allows you to do this.
```

## Project 4-8

### Step 5

What are the permissions on the `utest2` file?
<!-- TODO -->
```
-rw--rw-----
```

What are the permissions on the `udir2` file?
<!-- TODO -->
```
drwxrwx----
```

## Project 4-9

### Step 7

Insert the screen capture

<!-- TODO -->
![Alt Text](media/file.png)

## Project 4-10

### Step 7

Which special permission is set on this directory?
<!-- TODO -->
```
Only the file owner/creator can delete files, but all users can create files
```

Who can add or remove files to and from this directory?

<!-- TODO -->
```
The user
```

### Step 17

Insert the screen capture

<!-- TODO -->
![Alt Text](media/file.png)

## Project 4-11

### Step 3

Insert the screen capture

<!-- TODO -->
![Alt Text](media/image%20(25).png

## Command Reference



<!-- TODO -->
```
your-command
your-command
your-command
```

## Discovery Exercises

Solve the following problems from the textbook under Discovery Exercises.
Search the internet for answers if you don't know.

### Exercise 3 

<!-- TODO -->
```
a.         find / -name “test*”

b.         find /awk -f /-r

c.         find /usr -size+50k

d.         find /usr -size-70k

e.         find / -type l

f.          find /var -amin -60

g.         find /var -atime -6

h.         find /home -type -f empty

i.          find /etc -group bin
```

### Exercise 4

<!-- TODO -->
```
a.         644

b.         444

c.         076

d.         356

e.         667

f.          240
```

### Exercise 5

O: permitted; X: not permitted

| Filename | Mode        |       | Read | Edit | Execute | List | Delete |
|:---------|:------------|:------|:----:|:----:|:-------:|:----:|:------:|
| sample2  | `r--r-----` | User  |      |      |         |      |        |
| sample2  | `r--r-----` | Group |      |      |         |      |        |
| sample2  | `r--r-----` | Other |      |      |         |      |        |
| sample3  | `rwxr-x---` | User  |      |      |         |      |        |
| sample3  | `rwxr-x---` | Group |      |      |         |      |        |
| sample3  | `rwxr-x---` | Other |      |      |         |      |        |

Sample2: user has delete permissions. other does have list permissions.
Sample3: other has list permissions

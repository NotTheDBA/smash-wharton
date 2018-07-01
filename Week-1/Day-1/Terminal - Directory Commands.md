
Follow along as I demonstrate these commands, then try them yourselves:

Press and hold the CTRL key, then pres the "backtick" key.  This opens and closes our "Terminal", or command window.)
```
CTRL+`
```
Type "ls" in the terminal, then press the [Enter] key.   "ls" lists the files and folders where our terminal is pointed.

```
ls  [Enter]
```

Type "cd", which means "change directory", then space and "c:" which is the root of your hard drive.

```
cd c:  [Enter]  
```

Now type "ls" and enter again...  notice how the output is different.


```
ls  [Enter]
```


Now type "mkdir Source" and enter...  This makes a directory, or "folder" for us - "mkdir" - called "Source".


```
mkdir Source  [Enter]
```

Now change directory to our Source folder.  Notice that we don't need the colon ":" caracter for the folder, only for our root c:.  Then use ls to see the folder is empty.

```
cd Source  [Enter]  
ls  [Enter]
```

Now use mkdir to create two more folders.  You can do this with one command:

```
mkdir Git Lessons [Enter]
```

Now change directory to our Git folder, and make two more directories.

```
cd Git  [Enter]  

mkdir Portfolio Project [Enter]
```

Now we want to change directories to our Lessons folder...  but we can't use cd Lessons, because Lessons isn't below Git!

Instead, we can use two dots (periods) to first go up one level, like this:

```
ls [Enter]  -- notice the contents

cd ..  [Enter]

ls [Enter]  -- notice the contents

cd Lessons  [Enter]

mkdir W1-D1 W1-D2 W1-D3 W1-D4 [Enter]
```

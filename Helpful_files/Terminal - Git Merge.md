# Megergin Git Commands
## Retrieving changes from the server (remote repo)

Follow along as I demonstrate these commands, then try them yourselves:

Press and hold the CTRL key, then pres the "backtick" key.  This opens and closes our "Terminal", or command window.)
```
CTRL+ ``
```
Change directory to your source folder.
```
cd c:\source
```
When you want to make a local copy of any git repository, you can use this general format;
```
git clone <repo link>
```

For example (let's all do this one together):  

```
git clone git@github.com:NotTheDBA/smash-wharton.git
```

Sometimes your local version will be out of date, you can check and update it using these commands...

"git fetch" finds out if there are any changes.
```
git fetch
```

"git pull" brings the latest versions down to our local machine. "origin master" tells git we want to pull the main branch to our local machine.  (We will cover branching later!)
```
git pull origin master
```

Notice how there are new folders and files in our Source directory.

# Terminal - Git Commands
## Checking in your changes

From today foward, you will be expected to check in your changes to Github by the end of the day!

First, we will check the status of your code:

```
git status
```
You will probably see something like this:
```
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        index.html

nothing added to commit but untracked files present (use "git add" to track)
```

First you will add your changes to the git repo.  You can use this command:
```
git add .
```
(notice the period at the end...) 
OR
```
git add -A
```
(the capital A is important here...)

They do basically the same thing, add all your changes.

Now you need to "commit" your changes.  You're telling git that these are ready.   You will need to add a comment to your commit, so that anyone who looks at it will know what the changes were...

You will add the comment with the flag "-m" (m, is a comment, or message), then the actual message in quotes.   

Example:

```
git commit -m "First check-in for my Portfolio.  Added the index page."
```

Now, you need to push your changes up to your repository.

Pushing is the opposite action from pulling...   Pulling gets the latest changes from the server to our local machine.   Pulling puts our latest changes from our local machine to the server.   Sometimes you will need to do both on your projects!

```
git push origin master
```

_Make a note of this command.   You will need to use it every day we have class!_
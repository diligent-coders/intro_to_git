# Intro to Git Course

Welcome to the Diligence Media/Gaming community "Intro to Git" learning repo! This short course will give you a quick intro to Git.

## Lesson

*What is Git?* - The first part of this course is simple. We won't need to know every single last detail about Git, but we'll want a brief understanding of what it is to get started. First, all you'll have to do is [2 Minute Video](https://www.youtube.com/watch?v=2ReR1YJrNOM) explaining briefly Git is.

## Homework

1) *Make a Github Account* - Go to [Github](https://www.github.com) and make an account. Github will be the place where we will save all of our code and serve as a public record of our learning. After you've created an account, post your username in the #learn_programming channel on Discord.

2) *Install Git on Your Machine* - After that, install Git itself. Click [this link](https://github.com/git-guides/install-git) for the official instructions for installing Github. be sure to follow the instructions for your machine. Ping the [Discord channel](https://discord.gg/rRGukhvEYE) if you have any issues.

3) *Install Code Editor* - After that, install a code editor app. Some good ones are [Atom](https://atom.io/), [Sublime](https://www.sublimetext.com/), [VS Code](https://code.visualstudio.com/) but its up to you.

4) Create a note on your computer or some place to save the following commands as a "cheat sheet" for Git:

```
# Creating/Cloning Repos
git init  # Initialize a local Git repository
git clone ssh://git@github.com/[username]/[repository-name].git # Pulls a repository down from Github into the local directory

# Status and Saving
git status  # Check status
git add [file-name.txt] # Add a file to the "staging" area. The staging area 
git add -A  Add all new and changed files to the staging area
git commit -m "[commit message]"  Commit changes
git rm -r [file-name.txt] Remove a file (or folder)

# Branching and Merging
git branch  List branches (the asterisk denotes the current branch)
git branch -a List all branches (local and remote)
git branch [branch name]  Create a new branch
git branch -d [branch name] Delete a branch
git push origin --delete [branch name]  Delete a remote branch
git checkout -b [branch name] Create a new branch and switch to it
git checkout -b [branch name] origin/[branch name]  Clone a remote branch and switch to it
git branch -m [old branch name] [new branch name] Rename a local branch
git checkout [branch name]  Switch to a branch
git checkout -  Switch to the branch last checked out
git checkout -- [file-name.txt] Discard changes to a file
git merge [branch name] Merge a branch into the active branch
git merge [source branch] [target branch] Merge a branch into a target branch
git stash Stash changes in a dirty working directory
git stash clear Remove all stashed entries
Sharing & Updating Projects
Command Description
git push origin [branch name] Push a branch to your remote repository
git push -u origin [branch name]  Push changes to remote repository (and remember the branch)
git push  Push changes to remote repository (remembered branch)
git push origin --delete [branch name]  Delete a remote branch
git pull  Update local repository to the newest commit
git pull origin [branch name] Pull changes from remote repository
git remote add origin ssh://git@github.com/[username]/[repository-name].git Add a remote repository
git remote set-url origin ssh://git@github.com/[username]/[repository-name].git Set a repository's origin branch to SSH
Inspection & Comparison
Command Description
git log View changes
git log --summary View changes (detailed)
git log --oneline View changes (briefly)
git diff [source branch] [target branch]  Preview changes before merging
```

5) *What's next?* - Congratulations, after youve've got Git setup, you're one step forward in your coding journey and you'll be able to more effectively collaborate with one another and save our work.

## Further Reading

[Getting Started - What is Git](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)

## Contributing
Diligent Coders welcomes contributions! Fork the repo and open a pull request.

## Contact
Diligence Media is a group of friends with a background in gaming, music production and performance, graphic design, and general multimedia. Please join us on [our Discord Channel](https://discord.gg/rRGukhvEYE) for direct communication regarding this course.

## FAQ
<sub><sup>
1. _Who teaches this course?_ <br>
Diligence programming mentors! At the moment, that'll primarily be [ZASman](https://github.com/ZASMan) with some assistance from Diligence team members with programming experience. We're basically just a group of friends trying to have fun and help each other learn some new skills.<br>

2. _I have a learning disability, how can I succeed in this course?_<br>
Course mentors aren't trained educators but will collaborate with one another and try to help you to the best of their ability.<br>

3. _I feel like a failure with technical things and I've had some bad experiences in the past, is this right for me?_
Arnold Schwarzanagger once said, _"Don't be afraid to fail. ... You can't always win, but don't be afraid of making decisions."_ You made the decision to come here to try and learn, so why not just give it a chance? The best thing that could happen is that this sets you on a path to learning programming and a new job.

4. _I'm not a great classroom learner, how do I know I'll be able to handle this course?_<br>
While we'll meet and correspond and regularly as you can, the beauty of an open source and online course like this is that you can follow along and submit assignments at your own pace, and the course mentors will get back to you.

5. _Where can I get some help with this?_ <br>
Come say hello at [our Discord Channel](https://discord.gg/rRGukhvEYE)
</sub></sup>

# How to publish to GitHub Pages

Check your folders current `git` status using: `git status`

## If you have not created the git repo yet

`git init`

## Add files to git

Other wise just add all your files and commit:

`git add your_file_names.html`

`git commit -m "added some files"`

Note you can use `git add .` to add all the files. Do a `git commit -m "your message here..."`

## Create a gh-pages branch

`git branch gh-pages`

## Move into the gh-pages branch

`git checkout gh-pages`

## Link your local repo to a remote repository

Copy the commands from GitHub after you created a repository there...

The command looks like this:

`git remote add origin ...`

## Now push it to GitHub

`git remote push origin gh-pages`

It should now prompt you for your GitHub token in a page behind other pages...

Create GitHub Token on GitHub if you don't have one already.

### Create a GitHub token

* Click on your profile
* Click on Settings
* Click Developer Settings - at bottom left of the screen
* Click on Personal Access Token
* Enter name for your token & select a duration
* Select the repos checkbox
* Click on Generate Personal Access token

After this your page should be available online...

Get the URL in your GitHub repository under Settings -> Pages


## Add an index.html file

Add an `index.html` file in your project using the file in this repo as an example, but style it better than mine.

## How to remove a git repo in the wrong folder

Check if your home folder or desktop or project folder was made a git repo by mistake by using `git status`.

If it is delete the .git folder by using this command:

```
rm -rf .git
```
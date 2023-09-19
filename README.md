# [Master Git and Github - Beginner to Expert](udemy.com/course/git-and-github-for-absolute-beginners/)

## GIT Commands
### SETUP
#### Configuring user information used across all local repositories.
> Set a name that is  identifiable for credit when review version history 
```
git config --global user.name "[firstname lastname]" 
```
> Set an email address that will be associated with each history marker
```
git config --global user.email "[valid-email@mail.com]" 
```
> Set automatic command line coloring for Git for easy reviewing
```
git config --global color.ui auto 
```
> Show GIT user name and email
```
git config user.name
git config user.email
```

### INIT
#### Configuring user information, initializing and cloning repositories
> Initialize an existing directory as a Git repository and enables local folders to execute git commands.
```
git init
```
> Retrieve an entire repository from a hosted location via URL

```
git clone [url]
```

> Shows the url repo, shows nothing if there's no remote url.
```
git remote --v 
```
> Associate a remote repository with local Git repository
``` 
git remote add  origin REPOSITORY_URL

```
### STAGE 
```
git add .
git commit -m'message'
git push
git log
git log --oneline
git status
git checkout commit_id


```

`.gitignore file is used to skip files while sending to remote repo from local repo `

## 2 spaces after the end of the backtick creates new line for next 
`git add .`  
`git commit -m`  
`git push`

## We can write in multiline using 3 backticks 
```
git add .
git commit -m"message"
git push
```
## We can write html and CSS here
```html
<h1>HTML Element </h2>
```

```css
h1{
    color: red
}
```

## We can create ordered and unordered list here
### Todo: 
1. Add all commands according to their tasks
2. Add an image
3. SSH Key

- Unordered 1
- Unordered 2
   - Sub 1
   - Sub 2
     - Sub 2.1
- Unordered 3
 
<p style='color:red'>This is some red text.</p>
<font color="red">This is some text!</font>
These are <b style='color:red'>red words</b>.
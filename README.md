# Create your own HTML/CSS - Brag Sheet

You homework is to start working on a brag sheet for later showing to potential employers.

## Clone Repo

type in terminal (text inbetween <> needs to be personalized to your project)

```
git clone https://github.com/bluerails/bragsheet.git
cd bragsheet
git checkout -b <branch name>
```

## Create HTML and CSS

### Open your folder in Sublime Text
 - open Sublime and select File, Open...
 - Select the folder you just created for your repo
 - create HTML and CSS files in sublime, they can be saved directly to your folder

### Set up your HTML
- make sure to have a head and body (look online for examples if you get stuck)
- create div tags and other elements to setup your page
- add photos, links to other websites and any else you'd like to include
- include Your Name, a selfie, different level headings(h1,h2,h3), and an unorder list of atleast 5 acomplishments

### Set up your CSS

Note the HTML file includes the css link in the head:

```HTML
<head>
<link rel="stylesheet" type="text/css" href="application.css">
</head>
```

- change the background color
- style your headings
- align the different div tags, photos and text on the page in a visually pleasing way. Check out the "Learn CSS Layout" and the w3schools links below if you get stuck.

## When you are pushing to Github

- git add .
- git commit -m “Your message”
- git push origin <branch_name>


We will be looking at a couple students' webpages, there's no pressure to make it amazing by that time. We are all learning at our own pace but try to hav some fun with it.

###### Go back to the CSS Challenge there are other tools at the bottom of the page.

## CSS helpful links **the important ones** (look at these if you get stuck!)

- [Learn CSS Layout](http://learnlayout.com)
- [w3schools](http://www.w3schools.com/css/default.asp)
- [devtools](http://discover-devtools.codeschool.com)

## more helpful links

- [MDN position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- [MDN display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
- [MDN float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
- [CSS Display Playground](http://quirksmode.org/css/css2/display.html#link9)
- [Inline Elements: Width, Height, Padding & Margin](http://www.maxdesign.com.au/articles/inline/)
- [CSS Floats](http://alistapart.com/article/css-floats-101)
- [Clear Floats with `overflow: hidden;`](http://colinaarts.com/articles/the-magic-of-overflow-hidden/)
- [CSS Positioning](http://alistapart.com/article/css-positioning-101)
- [Typesetting a Short Article with CSS](https://medium.com/designed-thought/99033116fe92)
- [Pesticide](http://pesticide.io/) A stylesheet and Chrome extension to help with CSS debugging
- [HTML & CSS Resources](https://gist.github.com/jenmyers/a6bb9ea6233c6c5a9edb)

# terminal commands

I suggest making flashcards for each of these "terminal/command prompt" commands

```
pwd             - stands for ‘Path of Working Directory’. Find out where you are by typing
ls              - list the contents of a particular directory
cd PATH         - change to another directory
"cd" or "cd ~"  - navigate to your home directory
cd -            - navigate to the previous directory (or back)
cd ../          - To move up one directory
cd ../../       - To move up two directories
rm              - remove or delete a file in your directory.
rmdir           - delete an empty directory. To delete a directory and all of its contents recursively, use rm -r instead.
mkdir           - create directories. Example: "mkdir music" will create a directory called "music".
cp              - make a copy of a file for you. Example: "cp file foo" will make an exact copy of "file" and name it "foo"
mv              - move a file to a different location or will rename a file. Examples are as follows: "mv file foo" will rename the file "file" to "foo". "mv foo ~/Desktop" will move the file "foo" to your Desktop directory, but it will not rename it. You must specify a new file name to rename a file.
man             - show you the manual of other commands
```

BEWARE: any command that uses "sudo" or "-f" these can harm your computer or destroy your project.

Optional exercises for working with GIT
If you want to learn more about using Git go through [Learn Git Branching](http://pcottle.github.io/learnGitBranching/) or [Git Code School](https://www.codeschool.com/courses/try-git)

### Notes

#### important terms
```
Repo or Repository
  The file that you are working on it can include other files.
Branch
  A copy of the file you can make changes to
  Does not affect the other file.
Fork
  Copying a repository to your own account to make changes
Commit
  All changes up to that point bundled together
Merge
  Takes the commits of two or more people and combines them
Merge Conflict
  When there is a problem with merging the two branches
  ex. two people worked on the same paragraph
Pushing
  Rending your local work online ex. GitHub
Pull Request
  Requesting the changes that you made be merged with a repo
```
#### important git commands
```
Git init
  Creates a new repository in your local project
Git remote add origin <GitHub URL>
  Adds a connection between local repo and the one on GitHub
Git add .
  Stages changes and makes git aware that there are changes to the repo
Git commit -m “<commit message>”
  Tells git you have made changes and the message is where you say what you did.
Git push origin <branch>
  sends changes up to GitHub
Git status
  Tells your current state, what has been added, untracked changes, what is staged, and current branch. Keep useing this command to check where you are in the commiting process
```

## Stretch Challenge: wire framing

Here is a free wireframing tool to help you design the layout of your website [Click Here](https://wireframe.cc/)
Wireframe you site before writing your HTML.

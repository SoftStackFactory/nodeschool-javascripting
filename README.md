# JAVASCRIPTING

> Learn JavaScript by adventuring around in the terminal.  

> _Looking for more interactive tutorials like this? Go to [nodeschool.io](http://nodeschool.io)._

## Get help
Having issues with javascripting? Get help troubleshooting in the [nodeschool discussions repo](http://github.com/nodeschool/discussions), or on gitter:

[![Gitter](https://img.shields.io/gitter/room/gitterHQ/gitter.svg)](https://gitter.im/nodeschool/discussions?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Overview
The goals of this lesson is to help you becomre more comfortable with cloud9, bash git and basic javascript.

### Create Directories For Course
Run all the steps in the terminal
1. Create a folder named: **challenges** 
2. **change the directory** into challenges folder
3. Create another folder **week-1**
4. **change the directory** into week-1
5. Create another folder **javascripting**
5. Clone then clone this repository into **javascripting** folder
```
$ git clone https://github.com/SoftStackFactory/nodeschool-javascripting.git
```

Bash Commands Hint:
* **cd** change directory
* **mkdir** create new folder


### Install `javascripting` with `npm`

Open your terminal and run this command:

```
npm install --global javascripting
```

The `--global` option installs this module globally so that you can run it as a command in your terminal.

#### Having issues with installation?

If you get an `EACCESS` error, the simplest way to fix this is to rerun the command, prefixed with sudo:

```
sudo npm install --global javascripting
```

You can also fix the permissions so that you don't have to use `sudo`. Take a look at this npm documentation:
https://docs.npmjs.com/getting-started/fixing-npm-permissions

## Run the workshop

Open your terminal and run the following command:

```
javascripting
```

You'll see the menu: testing

![javascripting screenshot](screenshot.png)

Navigate the menu with the up & down arrow keys. 

Choose a challenge by hitting enter.

### Take a look at this gif that shows the first challenge:

![first challenge](javascripting.gif)

Create a file when you start a challenge
Ex: challenge-1.js
We can use the command **touch** in the terminal to create a file.
```
$ touch challenge-1.js
```
To test your code and pass the challenge run in your terminal:
```
javascripting verify.js challenge-1.js
```


### Lesson Flow Review
**Note** <filename> is a placeholder replace everything with the exact name.
```
touch <filename>
touch challenge-1.js
```
1. Create a new file for the challenge
File name example: challenge-1, challenge-2
``` 
$ touch <filename>
```
2. Test your solution with:
```
$ javascripting verify <filename>
```
3. Now once we have passed the javascripting test we can check the status of our the files that have changed in the terminal run:
```
$ git status
```
Files in red font are changes to files that are not staged and will not be apart of the commit
4. Let **add* our changes so they will be apart of the commit.
```
$ git commit -m "message about what you did here"
```
5. Now run the javascripting program to select a new lesson:
```
$ javascripting
```



## Need help with an exercise?
Ask for help in glip or try the discussion boards below

Open an issue in the nodeschool/discussions repo: https://github.com/nodeschool/discussions

Include the name `javascripting` and the name of the challenge you're working on in the title of the issue.



## License

MIT
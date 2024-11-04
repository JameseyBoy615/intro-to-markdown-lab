# How to create a file using the Terminal

![Computer with terminal](https://images.unsplash.com/photo-1493020258366-be3ead1b3027?q=80&w=1480&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

The Terminal is a **CUI** or a text-based interface. The Terminal provides a powerful and efficent way to interact with your computer. Compared to **GUI**, terminals provide quick access to all available commands, making it easier and faster to perform complex tasks.

For this example we are using a **Linux** based termminal with **Oh My Zsh** installed.

## 1. Understanding the Terminal

![Linux Terminal](./Linux-Terminal.png)

Notice the green `➜` and the blue `~`, followed by your cusor.

The `➜` represents the code input line.

The `~` represents your current directory location.

The `|` that follows is where you enter any commands

### Basic Terminal Commands

| Command | Description |
| ------ | ----------- |  
| pwd | shows current location |
| ls | shows contents within directory |
| cd | change directory |
| mkdir | make directory |
| touch | create file |
| rm | delete file |

## 2. Determining where to place file

When we first open the terminal we are placed within the **root** directory also known as the home directory. In most cases we do not want to crowd up our root directory with a bunch of files so in this example we are going to create a directory that will contain our new file.

These are the steps to create a new directory.

* First we must enter this command that creats the directory
 ```
 mkdir (directory name)
 ```

***Example***

```
 mkdir how-to-create-file
```
Notice when entered the terminal seems to not have given any feedback. This is normal. to make sure our command worked we can use the `ls` command to confirm that it was created. If we were to enter a incorrect command we would see a red `➜ `.

* Next, to enter the directory we can use this command

```
cd (directory name)
```
***Example***

```
cd how-to-create-file
```
Notice how the `~` has changed displaying our new location. we can also use the `pwd` command to output our current location

## 3. Making the File with the Terminal

Now that we are in the directory where we want the file in, we can finally create a new file

* To create a new file we can use the `touch` command

```
touch (filename).(file type)
```

***Example***

```
touch index.html
```
Congradulations! You created a new file within the Terminal.

For more information and commmands that you can use within the terminal,. checkout a more [detailed tutorial](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview) here.


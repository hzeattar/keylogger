# A simple keylogger for Windows, Linux and Mac

Welcome to the simple keylogger repo! A keylogger is a program that records your keystrokes, and this program saves them in a log file on your local computer.

Check out below to learn how to install them. These keyloggers are simple and bare bones, however they work great! Feel free to fork and improve it if you want.
Currently, there are three keylogger programs for the major operating systems; Windows, Mac and Linux.

## Contents
- [Windows installation guide]
- [Mac installation guide]
- [Linux installation guide]
- [Check out the site for more information]

Or, view the `README.md` file in each programs folder for more up to date information.

## Windows
To change visibility of the window set the `#define` in line 13 to `visible` or `invisible`.

Simply compile into an .exe, and then run. Visual Studio is good for this.

- `invisible` makes the window of the logger disappear, and it also starts up hidden from view. Note that it is still visible in the task manager.
- `visible` is visible, and the window does not close when typing. Great for testing it out.

Both of these save the keystrokes to a .txt file when closed.

> Note that sometimes your compiler may throw up errors. If it does, keep compiling - the program still works. 
## Mac
See [Casey Scarborough](https://github.com/hzeatar/keylogger).

## Linux

### Usage
```
  pip install -r requirements. txt
  keylogger.py
```

## How to run it

By running `nohup python3 keylogger.py &` command, it'll start to log your strokes:
The meaning of nohup is ‘no hangup‘.
When nohup command use with ‘&’ then it doesn’t return to shell command prompt after running the command in the background. 
```
$~/Keylogger/linux$ nohup python3 keylogger.py &
[1] 12529 //this is the keylogger's PID (process ID)
$:~/Keylogger/linux$ fg

```

The Keylogger is now running! It will log your strokes to a file .
Stop it by typing the command `fg` then hitting `CTRL+C`

or

`kill {PID}` for example `kill 12529`


---

---
#### Uses

Some uses of a keylogger are:

- Personal Control and File Backup: Make sure no one is using your computer when you are away.
- Self analysis

---

Feel free to contribute to fix any problems, or to submit an issue!

Please note, this repo is for educational purposes only. No contributors, major or minor, are to fault for any actions done by this program.

Don't really understand licenses or tl;dr? Check out the [MIT license summary](https://tldrlegal.com/license/mit-license).

Distributed under the MIT license. See [LICENSE](https://github.com/hzeatar/Keylogger/blob/master/LICENSE.txt) for more information.

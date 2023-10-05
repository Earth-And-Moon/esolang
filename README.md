# esolang
A small esoteric programming language, 100% written in Python (implemenations in other programming languages might come soon).

Welcome to Esolang, a tiny esoteric programming language!

## Installation
Open the <a href="https://github.com/Earth-And-Moon/esolang/releases/">release list</a> and select a version you want to download.
The latest version contains the most up-to-date patches and features, thus it is recommended to download that.
Now you see 3 files (and the source code):
`esolang.exe` - the core program
`esolang.zip` - the core program + examples
`examples.zip` - example scripts
Download one (or more) of them, and, if it's a .zip, extract it somewhere.
Now you have successfully installed it!

## How to use Esolang?
Unlike many other programming languages, Esolang doesn't have a command line interpreter and an IDE.
The only way to execute a script is to pass it as an argument to <b>esolang.exe</b>, like this:
`esolang.exe script.eso`, by dropping it on `esolang.exe`, or by right-clicking it, selecting "Open with" and choosing `esolang.exe` there.

## Programming in Esolang
Esolang has only memory for **one** one number at a time - it uses a variable which is named `mem` which has a value of `0` at start.

Esolang uses 3 (actually 4) commands.

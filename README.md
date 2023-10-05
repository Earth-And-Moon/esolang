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
Esolang has only memory for **one** one number at a time - it uses a variable `mem` that has a value of `0` at start.
There are 5 commands available in the programming language:

<table>
  <thead>
    <tr>
      <th>Command</th>
      <th>Explanation</th>
      <th>Python equivalent</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>+</td><td>Increases the value of mem by 1.</td><td>mem += 1</td>
    </tr>
    <tr>
      <td>-</td><td>Decreases the value of mem by 1.</td><td>mem -= 1</td>
    </tr>
    <tr>
      <td>.</td><td>Writes the Unicode char with the same number as mem to stdout, or an empty string if mem is -1.<br>Causes the script to stop running if mem is less than -1 or greater than 1114111.</td>
      <td>print(chr(mem)) if mem != -1 else print("")</td>
    </tr>
    <tr>
      <td>,</td><td>Takes input from the user and sets the value of mem to the Unicode char code of the first char of the input, or to -1 if the user entered empty input.</td>
    </tr>
    <tr>
      <td>any other character<br>(also spaces and line-breaks!)</td><td>Causes the program to exit</td>
    </tr>
  </tbody>
</table>










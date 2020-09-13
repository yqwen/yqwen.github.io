---
layout: post
title:  "Notes for Jupyter Notebook on Mac"
date:   2020-09-12
permalink: /tech/jupyter-notebook-usage
categories: tech
---

This semester, I'm getting back to Python for data science to work on the data visualization project on geographic data. Haven't been using Jupyter Notebook for almost two years and it's also my first time to use it in MacOS, so I'm writing this to take some notes for quick references.

# Installation
Install from [Anaconda](https://www.anaconda.com/products/individual) using MacOS Python 3.8 64-Bit Graphical Installer.
Simply follow the instructions on the installer and install it under `/Users/w/opt/anaconda3`.
Open Jupyter Notebook from Anaconda Navigator. 
Or, go to the anaconda directory in the terminal, execute `bin/jupyter-notebook`.
Not shortcuts found yet :(

# Install Packages
If I run `pip3 install` in terminal, the packages cannot be found in Jupyter. To see where Jupyter finds its packages, run
```
import sys
print (sys.path)
print (sys.executable)
```
in jupyter to see its path.


Solve the package problem finally by running `!pip3 install` in Jupyter cells.

# Shortcuts
## Edit Mode
| Operation | Shortcut   |
|-----------|------------|
| switch to command mode | Esc |
| run cell, select below | shift + enter |
| run cell | ctrl + enter |
| run cell, insert below | option + enter |
| split cell | ctrl + shift + minus |
| go to cell start | cmd + up |
| go to cell end | cmd + down |
| go one word left | shift + left |
| go one word right | shift + right |
| delete word before | shift + back |
| delete word before | shift + delete (for keyboard) |


## Command Mode
| Operation | Shortcut   |
|-----------|------------|
| switch to edit mode | enter |
| show keyboard shortcuts | H |
| find and replace | F |
| change cell to code | Y |
| change cell to markdown | M |
| change cell to raw | R |
| select cell above | up or K |
| select cell below | down or J |
| insert cell above | A |
| insert cell below | B |
| cut selected cells | X |
| copy selected cells | C |
| paste cells above | shift + V |
| past cells below | V |
| delete selcted cells | double D |
| undo cell deletion | Z |
| toggle line numbers | L |
| toggle output of selectes cells | O |
| interrupt kernel | double I |
| restart kernel | double O |
| scroll notebook up | shift + space |
| scroll notebook down | space |

The full list of shortcut are [here](/files/jupyter-shortcuts.pdf)
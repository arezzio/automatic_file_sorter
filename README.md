
## Project Goal(s) 🎯

This project aims to create a small, user-friendly tool to help people with organizing their files through use of simple algorithms that provide a number of sorting options.

Specifically, this project looks to provide the user with:

- A program that automatically moves/copies and sorts files from user-designated source to destination directory
- A user-friendly interface for managing files
- The option to automatically move/copy and sort files from removable devices
- The option to automatically sort directories or partitions as content is added, changed or removed

## Installation & Usage 💻

First, clone this repository:
```bash
# Clone the repository
$ git clone https://github.com/Kreateer/automatic-file-sorter
```

### Linux

Make sure you have Python 3.8+ installed on your system:
```bash
# Install Python 3.8
$ sudo apt-get install python3.8
```

You may also need to install the `tkinter` module for Python:
```bash
# Install tkinter for Python 3
$ sudo apt-get python3-tk
```

Next, install the dependencies:
```bash
# Install dependencies
$ pip3 install -r requirements.txt
```

Finally, locate ``fmain.py`` and run the script through an IDE or through console:
```bash
# cd to where 'fmain.py' is located
$ cd <clonelocation>/automatic-file-sorter/scripts

# run 'fmain.py'
$ sudo python3 fmain.py
```
Once you run the program, just follow the GUI instructions.

### Windows

Make sure you have Python 3.8+ installed.
If you don't, you can download the Windows release from the [official Python site](https://www.python.org/downloads/windows/).

Once Python is installed, you need to install the dependencies using pip.

*IMPORTANT: If you're using an IDE like PyCharm, preferably you can use the IDE options to install packages in a virtual environment*

In Command Prompt, type:
```bash
pip install -r requirements.txt
```

Then simply launch `fmain.py` through an IDE or through Command Prompt:
```bash
#cd to where 'fmain.py' is located
cd <clonelocation>/automatic-file-sorter/scripts

#run 'fmain.py'
python fmain.py
```
Once you run the program, just follow the GUI instructions.

## Compiling Into Executable ⚙️

- If you wish to build the source yourself and run the program from an **executable** instead of running the script everytime, you can use [PyInstaller](https://www.pyinstaller.org/) to compile the script into an **`.exe`** file.

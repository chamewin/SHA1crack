# SHA1Crack

SHA1Crack is a Python 2.7 program 
for brute forcing a SHA1 hash.

## Installation

**OS X & Linux:**

Download the latest Python 2.7 [here](https://www.python.org/downloads/release/python-2715/).

If you are running other versions of Python, you need to create a virtual environment for Python 2.7.

```bash
cd ~/PATH-TO-PROJECT-FOLDER
pip install virtualenv
virutalenv -p /usr/bin/python.2.7 venv
source venv/bin/activate
```

**Windows:**

Go [here](http://timmyreilly.azurewebsites.net/python-pip-virtualenv-installation-on-windows/) for Windows instructions because Windows is inferior to OSX and Linux and I can't be bothered to write instructions.

## Usage

**OS X & Linux:**

```bash
python hashcrack.py ARG1 ARG2
```

- ARG1 is the hash you are trying to crack.

- ARG2 is the salt in a salted hash. Leave this blank if you know the hash is not salted.

**Windows:**

```
C:\PATH-TO-PROJECT-FOLDER> python hashcrack.py ARG1 ARG2
```

- ARG1 is the hash you are trying to crack.

- ARG2 is the salt in a salted hash. Leave this blank if you know the hash is not salted.

## Hash Problems
- **Testing program hash:** b7a875fc1ea228b9061041b7cec4bd3c52ab3ce3
- **Medium hacker hash:** 801cdea58224c921c21fd2b183ff28ffa910ce31
- **Leet hacker hash:** ece4bb07f2580ed8b39aa52b7f7f918e43033ea1

    **Hint (Salt term):** f0744d60dd500c92c0d37c16174cc58d3c4bdd8e
    
## Answer to Hash Problems
- **Testing program hash:** letmein
- **Medium hacker hash:** vjhtrhsvdctcegth
- **Leet hacker hash:** harib
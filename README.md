# Sales-Bot

This is my AI project for my AI course.

## Initial Setup: How to Run This project

Clone repository or download zip.
Then create a virtual environment in the sales-Bot folder.
```
$ git clone https://github.com/mamun2425/Sales-Bot.git
$ cd Sales-Bot
$ python3 -m venv venv
$ . venv/bin/activate
```
Install dependencies
```
$ (venv) pip install torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```

Run:
```
$ (venv) python chat.py

```


If you run onece. Then every next time you have to only run this two command:


```
$ . venv/bin/activate
$ (venv) python chat.py

```

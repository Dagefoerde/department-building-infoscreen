# Infoscreens for Department Building Entrances (Prototype)

This is a prototype. It runs a python-based backend (e.g. on a Raspberry PI) and exposes a web-based frontend that is usually accessed from the same machine. 

Does not come with fancy screens or Raspberries.

To start the project, clone this repo and run:
```text
pip3 install -r requirements.txt # This will install flask.
npm install
```
in the project root directory, this will allow webpack to compile and concatenate all the dependencies and listen to all the changes you make. Make sure you have webpack exposed globally so the command can be accessed through the command line.

In a separate terminal, run:
```text
python server.py
```
This will fire up the flask server.

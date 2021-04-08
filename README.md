# Swap Meet: Buggy Edition!

## Bug Lowdown

There are two bugs in this code. One bug causes one test to fail, the other causes two tests to fail. 

The objective is to use your debugging skills to _understand_ **what** the program is doing wrong and **why**. At the end of the day, the easiest (and quite possibly best) way to fix the bugs would be to just copy/paste your to the buggy functions to replace this solution, so the emphasis here is **less on fixin**g the bug and **more on understanding**.

Have fun!

---------------------------------------------------------------------------------------------------------------------------------------

Everything below is just setup info copy/pasted from the original project. It's here for referene if you need it but it's nothing new :)

## One-Time Project Setup

Follow these directions once, a the beginning of your project:

1. Navigate to your projects folder named `projects`

```bash
$ cd ~/Developer/projects
```

2. "Clone" (download a copy of this project) into your projects folder. This command makes a new folder called `swap-meet`, and then puts the project into this new folder.

```bash
$ git clone ...
```

Use `ls` to confirm there's a new project folder

3. Move your location into this project folder

```bash
$ cd swap-meet
```

4. Create a virtual environment named `venv` for this project:

```bash
$ python3 -m venv venv
```

5. Activate this environment:

```bash
$ source venv/bin/activate
```

Verify that you're in a python3 virtual environment by running:

- `$ python --version` should output a Python 3 version
- `$ pip --version` should output that it is working with Python 3

6. Install dependencies once at the beginning of this project with

```bash
# Must be in activated virtual environment
$ pip install -r requirements.txt
```

Summary of one-time project setup:

- [ ] `cd` into your `projects` folder
- [ ] Clone the project onto your machine
- [ ] `cd` into the `viewing-party` folder
- [ ] Create the virtual environment `venv`
- [ ] Activate the virtual environment `venv`
- [ ] Install the dependences with `pip`

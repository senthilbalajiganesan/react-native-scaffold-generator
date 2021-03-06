# react-rn-scaffold-generator
React native scaffold generator using python.

## Content
- [Purpose](purpose)
- [Features](#features)
- [Installation&Setup](#installation&setup)
- [Usage](#usage)

## Purpose
-Are you following similar kind of file structure?

![Screenshot](https://s14.postimg.org/vtvnjgs7l/file_Structure.png)

Almost every time you create a new screen, you'll have to create a action and reducer and wire it to the screen,
which is really a redudant work and we programmers are here to automate not do same work again and again.

So here comes the scaffold generator for creating neccessary files(`actions,reducers,screens boilerplate`)
and directly start working on your view.

## Features
- Generate screen, action, reducer by just running a single command.
- Auto exporting of the files (actions and screens)
- Create new action and types
- Enter screen name and generate necessary files

## Installation&Setup (Assuming you already installed python).
1. Clone the repo or just download as zip.
`git clone https://github.com/senthilbalajiganesan/react-rn-scaffold-generator.git`

2. Open the folder and open index.txt and modify to `project_root_path/src`, so that points out the src folder of the project

## Usage

Note: You have to set up a file called `scaffold_root_path.txt` inside your python root folder and inside of that point out the project root_folder, for eg: your `scaffold_root_path.txt` should look like: `D:\\d\\python\\rn-scaffold`(where u cloned the repo)

1. Open the python root folder, usually in windows, it'll be like, `C:\Python27`(python 2.7)

2. To Create a screen and necessary files, run
 `python <react-rn-scaffold-generator_path>\add_new_screen.py`

 eg: `python D:\python_files\react-rn-scaffold\add_new_screen.py`

- Enter Screen name
- Enter reducer key for the screen

3. To create a new Action
`python D:\python_files\react-rn-scaffold\add_actions.py`

- Enter Screen name
- Enter action name
- Add comments for the type (optional)

4. To use the scaffold files(src folder having mentioned file strcture)
   that are already present, you can use following command,
   `python  D:\python_files\react-rn-scaffold\add_starter_files.py`

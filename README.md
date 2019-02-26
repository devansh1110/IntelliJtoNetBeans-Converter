# IntelliJ/NetBeans Project Converter

Make your Java applications created in IntelliJ easily compatible with NetBeans! 
You can also convert NetBeans Projects to IntelliJ! 

Coded by Devansh Kaloti, Edited by Will Assad

## Getting Started

Download this repository.

```
$ git clone https://github.com/devanshkaloti/IntelliJtoNetBeans-Converter
```

Switch into the project folder and install the software.

```
$ sudo python install.py
```

Make the project IntelliJ and NetBeans compatible from terminal or CMD!

```
$ convert /Users/johnexample/Desktop/myproject
```

That's all it will take to convert your project. Enjoy!

Don't hesitate to contact me at devansh@dksources.com if you have and questions or problems.

## Explanation

The `nbproject` is a required folder by NetBeans, where it keeps its project settings.
The only neccessary project build files needed are the `project.xml` and `project.properties`.

In `project.xml`, line 5 is changed to reflect the accurate name of the user's project. An unmodified copy is kept in the `template` folder, and the working copy of the settings are duplicated in the internal `nbproject` folder.

In `nbintellij.iml` is the required file by IntelliJ. 

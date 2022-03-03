# makestudio

Setup your Delphi Environment very easily - build your projects with more comfort

## What is MakeStudio

MakeStudio is a is a tool that enables developers and build masters to create an **automated build**, **deploying software**, **compiling and installing developer components**. Its essential power is the speed of creating build processes.
All Build commands are placed in **external plugins** which could be written either in any Win32 or .NET language. The interface to **create your own plugins** is fully documented and opensource.

## What are the differences to other Build tools

The original idea for makestudio was born during multiple installations of the Delphi IDE. Many packages had to be compiled and registered which took a lot of time. The first version for **automated setup of the Delphi IDE** was created and saved a lot of work and time.
This is still the case today until Delphi version 10.3 and within 2020 10.4

In the following years makestudio developed into a comfortable **open source build tool** for Windows projects. With focus not only on Delphi.

MakeStudio is especially designed to increase the speed in creating build processes and installing whole development environments on new PC's including programming components.
You simply **drop files from the explorer** window into the MakeStudio editor and **MakeStudio selects the best action by itself**.

Another outstanding feature are the **process control structures like if, while or loop**. With these control commands it is possible to create more flexible build, compile and installation sequences.

## Download

Latest binary setup can be downloaded [here](https://github.com/burkhard154/makestudio/releases)

## Screenshots

#### Setting up Delphi IDE

Setting up search path, registering all components in the IDE using one script.

![Setting up Delphi IDE](doc/images/screenshots/main_Delphi_Setup.png "Setting up Delphi IDE")

If you don't want to re write the all scripts everytime the compiler version has changed, you can use variables to install the packages correponding to your IDE version:

![Getting installed IDE version](doc/images/screenshots/auto_choose_packages.png "Getting installed IDE version")

#### Build and deploy project

Build the project, update version number, svn commit with comment, iss setup build, deployment... and more. All that with one script.

![Build and deploy project](doc/images/screenshots/main_build.png "Build and deploy project")

#### Script editor

![Script editor](doc/images/screenshots/Scripteditor.png "Script editor")

#### Commands tree

![Commands tree](doc/images/screenshots/Tree.png "Commands tree")

#### Delphi module

![Delphi module](doc/images/screenshots/Delphi_Module.png "Delphi module")

#### Add component folder dialog

![Add component folder dialog](doc/images/screenshots/Add_Component_Folder.png "Add component folder dialog")

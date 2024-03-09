# Templates

## Install
You can use the these editor scripts in your own project by adding this project as a [Defold library dependency](https://www.defold.com/manuals/libraries/). Open your game.project file and in the dependencies field under project add:  
https://github.com/Jerakin/editor-script-templates/archive/master.zip


## Editor Script
This a way for you to define your own templates that you can create with a right click in the Assets outline.

In the root of your project create a file called `templates.lua`, this file should be a module that returns a table with your templates with the name name you want in the context menu as the key and a relative path to the template file you have created.

For an example check out the template file [templates.lua](/templates.lua) and the template folder [templates](/templates) within this project.


![context-menu](/.github/context-menu.png)

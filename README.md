checkio-task-template
=====================

This is the base CheckiO template for user generated tasks.
It have fixed the folder structure so please be careful with
your file and naming conventions.


Tasks examples
--------------
https://github.com/Bryukh/checkio-task-transposed-matrix

Files definition
----------------

Below you can read an explanation for role of each file and folder inside the project.

description.html
----------------

This file is a description for your task.
Here, you should explain the goal for the task.
When writing this file, you must use proper HTML syntax for the description to
be readable on the site as it will be inserted on the task page as a block.

#### Story
The first paragraph or div has the class "story" --
this is some funny story about task, it does not need to
explain task's goal. A paragraph of div with the story
class does not show in the editor's task description.

#### Task's text
Next, you must write the main description of the task.
You can insert some images for explanation (see below for
information about images) and you can use html tags as 
em strong or pre to display formulas or example code.
Each paragraph or div element can have the class
"for_editor_only" or "for_info_only".

**"for_editor_only"** – means that the element will only show in the editor mode.

**"for_info_only"** – will only show up in the main task description.

#### Input and Output
This is short description of input and output data.

#### Example
This section gives some examples for the task.
You can use the pre tag with class "brush: python" for syntax highlighting.

#### Images
You can paste your images inside task.
The files for these must be placed inside the illustrations folder.
The link defined as src="/static/files/illustrations/*image-name.png*"
Illustrations should be created with specified colors from colors guide. (*color.pdf*)

#### Icons
Icons for task placed inside icon folder.
Icons are created as pair: 
**disabled.png** for unsolved tasks and **enabled.png** for solved tasks.
In the task runner you can see the both icons with click to it.
Icons should be created with specified icons' colors from colors
guide (*color.pdf*).
Icons must have size 128x128 and placed inside grey color with size 116x116 at center with border radius 10.
Use the given template.

task.json
---------
This is the task config with some useful info.

**task_name** -- The name of the task.

animation_cfg.json
--------
This file describes sizes of animation and how the tryit panel behaves.

**tryit\_results\_height** -- the height of tryit results. If you dont want to use tryit, then set it to 1.

**tryit\_results\_width**  -- the width of tryit results. If you dont want to use tryit, then set it to 1.

**animation\_panel\_width**  -- the width of animation's panel.

**console\_height** -- the height of bottom console. As usual, set it as tryit\_results\_height + 30

start_code.py
-------------

Here is the code which users will see as a starting template.

animation.js
------------

This file describe an animation for tests explanation or tryit.
It's **not necessary** to change it.

Further description of this will be added later.

animation.js
------------

This file describe styles for tests explanation or tryit.
It's **not necessary** to change it.

Further description of this will be added later.

template.html
-------------

This file describe layout and structure for tests explanation or tryit.
It's **not necessary** to change it.

Further description of this will be added later.


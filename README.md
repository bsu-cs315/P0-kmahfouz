# Project 0: Dodge the Creeps
A tutorial implementation by Karim Mahfouz

This project follows the [Your First Game tutorial from
godotengine.org](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html).

## Third-Party Assets

"art/House In a Forest Loop.ogg" Copyright &copy; 2012
[HorrorPen](https://opengameart.org/users/horrorpen), [CC-BY 3.0:
Attribution](http://creativecommons.org/licenses/by/3.0/). Source:
https://opengameart.org/content/loop-house-in-a-forest

Images are from "Abstract Platformer". Created in 2016 by kenney.nl,
[CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/). Source:
https://www.kenney.nl/assets/abstract-platformer

Font is "Xolonium". Copyright &copy; 2011-2016 Severin Meyer
<sev.ch@web.de>, with Reserved Font Name Xolonium, SIL open font license
version 1.1. Details are in `fonts/LICENSE.txt`.

## Project Report

The most challenging part of this project was, by far, pushing it to Github. The tutorial itself was fun and easy to follow; it was a good way to learn the basics of Godot. With what I thought was the most challening part out of the way, I thought that pushing the project was going to be the easy part. I was wrong: I was having a VCS nightmare. This is actually my second time writing this! However that commit went poof; I will explain momentarily. I made the mistake of thinking that pushing to Github through Godot was going to go like on any other platform. I was very much mistaken. After researching why it is that Godot couldn't find the right plugins, I learned that I do, in fact, need a plugin for it to find. I was very confused by the lack of built in Version Control. After downloading the plugin, I then faced the perils of figuring out where exactly to place the plugin. To my surprise, there was another 'addons' folder inside my 'addons' folder, that came downloaded with the plugin! It took me too long to figure that out. Finally, my VCS was finally working. Or so I thought... Then came trying to enable the plugin in Godot itself. For some reason, even though everything was in the right place, it still didn't work. It was hinting that there was a problem with the plugin itself. After an hour or two of trial and error/ research, I discovered two things. Firstly, There were many others facing my same problem. Secondly, I still had no idea how to fix it. As a last ditch effort, I decided to reinstall Git entirely. I do not know what about that the plugin liked, but suddenly, it was very happy. I was left even more confused, considering how I had been using Git all summer. But it worked! The plugin that is. Actually committing and pushing, on the other hand, was a whole different story. After many struggles, I ended up using the CLI to push my project, which finally got it on Github. It was naive of me to think that that was the end. While writing the first version of this report, I realised that one of my commits was not named correctly. At that point, I was debating giving up and playing a game instead of making one. However, I decided that I put in too much blood, sweat and tears into this to settle for a C. So, started researching how to change a commit that was not the most recent commit, which took me down a bit of a rabbit hole. Essentially, there was no safe way to do this. What I had to do was rebase the whole project, change the commit then force push the project to github. I was contemplating wether or not to risk it, but I decided to try. After multiple aborted rebase attempts, I was finally able to rebase successfully. Which also reset my README.md. Thank you for reading about my struggles. I apologize for the fact that it is late and that it reads a little like a poorly written horror movie ("Or so I thought..." etc.) I was hoping to make it somewhat entertaining to make up for the tardiness. 

## Self-Assessment
- [x] D-1: The repository contains a <code>README.md</code> file in its top-level directory.
- [x] C-1: The tutorial has been completed.
- [x] C-2: All commit messages comply with the required format.
- [x] B-1: Your <code>.gitignore</code> file is correctly specified in the repository.
- [x] B-2: No unnecessary/generated files are tracked in the repository. (not that I know of)
- [x] A-1: The project report is complete as per the instructions.

This work therefore merits an A.

# graphicsbygoff.github.io


Steps to take:

1. Download git (https://git-scm.com/download/win)
2. Open up your terminal on your computer
3. ```cd``` is a terminal command to change directories. ```cd``` into your desktop, whatever that route is, by doing ```cd /path/to/your/desktop```
4. Type this command ```git clone https://github.com/graphicsbygoff/graphicsbygoff.github.io.git```
5. Type ```cd graphicsbygoff.github.io```
6. You're now in your codebase. Type ```atom .``` to open your code in your editor
7. Now, make any kind of change in your ```index.html``` file.
8. Save this change.
9. Then, go to terminal, and type ```git add index.html```. This prepares your file to be added to github.
10. Then, type ```git commit```. It'll then put you through to another page (it's an editor inside terminal called "vim". Don't worry about it for now. 
11. Press ```i```. Then add a message detailing what kind of change you made. This makes a little message that helps document what you did.
12. After you're done, then press ```ESC : w q``` all in order, one after the other
13. then type ```git push origin master``` - you just pushed your changes to github!
14. Then, go to graphicsbygoff.github.io and refresh a couple times. your changes are there!

any time you want to make a change to code, just follow steps 8->13. A couple of times it'll become routine, don't worry if this is all really complex. It was for me!

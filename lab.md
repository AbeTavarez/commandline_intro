# Terminal Practice In Breakout Rooms

## Episode X: A New Terminal

> A long time ago in a Unix environment far, far away, young Jedi padawans who knew only of desktop software were seduced by the dark side of the Force to enter… The Terminal.

Follow the instructions below using all the CLI commands introduced in Fundamentals, class, or that you find on your own.




### Setup

 1. Open the CLI/Terminal/GitBash
 2. Create another folder called: galaxy-far-far-away
 3. Then create a file inside galaxy-far-far-away called `commands.txt`
 4. Paste the answer to each numbered question (i.e. the command(s) that accomplished the task) in `commands.txt`, once you get it to work.
 5. Remember, use the README.md file to help you or use the --help flag: `ls --help`.


===========================================================
#### Part I: Set the Scene
Complete all work inside the galaxy-far-far-away folder.

- Create a directory called `death_star`, and make the following files inside of it: `darth_vader.txt`, `princess_leia.txt`, `storm_trooper.txt`.

 - In galaxy-far-far-away, make a directory named `tatooine` and create the following files in it: `luke.txt`, `ben_kenobi.txt`
Inside of `tatooine` make a directory called `millenium_falcon`, and in it create: `han_solo.txt`, `chewbaca.txt`.


===========================================================
#### Part II: mv - rename
You can rename a file using the `mv` command.

 - Rename `ben_kenobi.txt` to `obi_wan.txt`.


===========================================================
#### Part III: cp - copy
You can copy a file from one location to another using the `cp` command.

Directories can be sibling (parallel to each other) or can be parents (the folder that contains the folder you are in).

 - Copy `storm_trooper.txt` from `death_star` directory to `tatooine` directory.


===========================================================
#### Part IV: mv - move
You can use the `mv` command to move files from one location to another. `mv` can be used for renaming, moving, or both.

 - Move `luke.txt` and `obi_wan.txt` to the `millenium_falcon` directory.
 - Move `millenium_falcon` out of `tatooine` and into `galaxy-far-far-away`.
 - Move `millenium_falcon` into `death_star`.
 - Move `princess_leia.txt` into the `millenium_falcon` directory.


===========================================================
#### Part V: rm - remove
######WARNING: *BE CAREFUL WITH rm!!! THERE IS NO "TRASH" IN THE UNIX CLI. WHEN YOU DELETE SOMETHING IT IS GONE FOREVER!!!*

You can use `rm` to delete a file.

 - Delete `obi_wan.txt`.


===========================================================
#### Part VI: all together

 - In galaxy-far-far-away, make a directory called `yavin_4`.
 - Move the `millenium_falconout` of the `death_star` and into `yavin_4`.
 - Make a directory in `yavin_4` called `x_wing`.
 - Move `princess_leia.txt` to `yavin_4` and `luke.txt` to `x_wing`.
 - Move the `millenium_falcon` and `x_wing` out of `yavin_4` and into `galaxy-far-far-away`.
 - In `death_star`, create directories for `tie_fighter_1`, `tie_fighter_2` and `tie_fighter_3`.
 - Move `darth_vader.txt` into `tie_fighter_1`.
 - Make a copy of `storm_trooper.txt` in both `tie_fighter_2` and `tie_fighter_3`.
 - Move all of the `tie_fighters` out of the `death_star` and into `galaxy-far-far-away`.


===========================================================
#### Part VII: rm -r: remove directories and everything they contain
###### WARNING: *BE CAREFUL WITH rm -r THERE IS NO TRASH CAN IN THE UNIX CLI. WHEN YOU DELETE SOMETHING IT IS GONE FOREVER*

### Before you hit enter, make sure are deleting the right thing, or you could accidentally delete the contents of your computer (it has happened). Check using `pwd`

###### This command will not typically ask you if you "really want to delete." It will just delete.

- Remove `tie_fighter_2` and `tie_fighter_3`.


===========================================================
#### Part VIII:
 
 - Touch or create a file in `x_wing` called `the_force.txt`
 - Destroy the `death_star` and anyone inside of it.
 - Return `x_wing` and the `millenium_falcon` to `yavin_4`.

##### Celebrate! You've reached the end of this exercise :)

===========================================================
#### You can skip this, I'll leave it here for later reference:
Commit and push your updated code:
"Add" your changes (prepare them to be "committed"):

$ git add -A
"Commit" your changes—any time you make a commit, you can always restore the files in the repo to that point:

$ git commit -m "Completed lab"
"Push" your commits to github:

$ git push origin master
Conclusion
You will "git" plenty of practice as we progress through this program, so if the concept of git/github still seems a little fuzzy at this point, rest assured you will soon "git" it once you "git" some more practice in. 😎
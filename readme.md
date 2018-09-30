# The Simpsons Bash

![Simpsons Intro](https://media.giphy.com/media/xT5LMSX0VGG2yHh8ek/giphy.gif)

## Learning Objectives

- Do more reps to become comfortable navigating the CLI.

![Terminal image](https://camo.githubusercontent.com/a5b3ba816df436e40d059312f25d388836d8890c/687474703a2f2f706978616261792e636f6d2f7374617469632f75706c6f6164732f70686f746f2f323031332f30372f31332f31332f34312f626173682d3136313338325f3634302e706e67)

## Background - Watch the Intro!
[Simpsons Intro](https://www.youtube.com/watch?v=XNzoJqzA6zM).

## Part 1 - Set Up our Directories for this class!
1. Open your terminal, in the root directory create a directory called `code`.  This is where you can put all your code for any projects, in and out of this class.
2. In the `code` directory create another directory called `wdi`, this will be where we put all content for this class.
3. In the `WDI` directory create 4 more directories called `labs`, `lessons`, `projects`, `misc`.  Your file structure is complete! We'll continue to use these directories to stay organized throughout the class.  Now that we're ready, let's create a directory for this lab:
4. Navigate to the path `~/code/wdi/labs` and create a new directory called `simpsons` where we will do all of the following work:


## Simpsons Activity
The more practice you have working in the terminal manipulating files and directories the better!

#### Creating the scene
The Simpsons are your average American family living in Springfield. Let's create the family's hometown, create a directory called `springfield` and `cd` into it. Once you've navigated into the directory let's create the family members, create the following files in your `springfield` folder:
<br>
-`Homer.txt`<br>
-`Marge.txt`<br>
-`Bart.txt`<br>
-`Lisa.txt`<br>
-`Maggie.txt`<br>

#### Remaking the Intro
1. When the show's intro starts the camera pans through the clouds and over the entire town. The view then focuses through the window of the elementary school where we find Bart in detention writing out whatever horrible deed he accomplished that day. Create a directory called `school` and move `Bart.txt` inside of it.<br><br>
2. Next the camera pans to the nuclear power plant where we find Homer mishandling what appears to be a radioactive core sample. Create a directory `power-plant` and move `Homer.txt` into it.<br><br>
3. Homer forgot his employee ID, so he needs to get a temporary pass. Let's use the 'echo' command to APPEND some text in the `Homer.txt` that says 'Work Pass: Homer J. Simpson' <br><br>
4. Use the 'grep' command to search `Homer.txt` for the phrase "Work Pass" just to be sure it is there.
5. Then we find Marge and Maggie together in the super market. Create a `market` directory and move Marge and Maggie inside it.<br><br>
6. The camera then pans to the band room in the school where we find Lisa crushing a sax solo. Traverse to the `school` directory, create a `band-room` directory, and move `Lisa.txt` into the `band-room` directory.  Challenge:  can you do this without leaving the band-room directory?<br><br>
7. We then find the family making their way home through the streets of springfield; Homer in his pink car, Marge and Maggie in the red car, and Bart on his skateboard. Traverse back to the `springfield` directory and create the directories for the each mode of transportation, and then place each respective party in that directory.<br><br>
8. The family finally makes their way back home and the hilarious couch gag ensues. Create a `home` directory inside of `springfield` and then create a `couch` directory within `home`. Then Move ALL of the family members to `couch`. BONUS - can you move the family members without going into any of the springfield sub-directories? (HINT - use relative paths! If in `springfield` directory, what does ` ls ` return? How about `ls power-plant `?)

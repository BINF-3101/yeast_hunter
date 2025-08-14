# yeast_hunter

Yeast are found everywhere in the environment! 

The yeast genomes we will be analyzing this semester were sequenced from yeast sampled from weird and wonderful places across the world. 

Maybe our class will even be able to sample later in the semester... 

In the interim, we will virtually sample on the HPC Cluster. 


**GOAL** You will find a yeast to study this semester and its secret "sequencing key". 

Each of you will have a unique yeast species, so if you find one that has already been claimed on the spreadsheet - keep looking!

Yeast Choice Sheet: https://docs.google.com/spreadsheets/d/1EuW_gBTT3Epl0tYhHk68UUEkpcYa0N2Q1w90fKzuhr8/edit?usp=sharing 


_HINT_ You may want to draw yourself a map of the world as you navigate through it. It may help you orient yourself


## Step 1 - Copy the yeast hunter activity to your directory

You do not need to make a new folder unless you would like to

```bash
cp /projects/class/binf3101_001/wild_yeast_hunter/yeast_hunter.tar.gz .
```

## Step 2 - Extract the activity

```bash
tar -x yeast_hunter.tar.gz
```

## Step 3 - Explore the Yeast Hunter world!

### Files in the world

There are 3 things you will encounter in the world

**Folders** Folders (also called directories) form the hierarchical structure of the world. You can refer to any files in your current folder/directory without adding the full folder path. 

**Readable Files** Readable files are standard text files that you can visualize (or print out) in the command line. 

**Executable Files** These files are programs (also called scripts) that use a programming language to execute a series of commands. 


### Commands to move around

**Enter a directory** - `cd directory_name`

**Return to your base directory** - `cd`

**Move to the previous directory** - `cd ..`


### Commands to execute files (environments)

If you want to "run" a executable environment file to check to see if there is a yeast there are two ways to do so. Let's use the environment `plum` as an example. 

**Add ./ to the command** - You can add `./` to an executable file to run it. `./plum`

**Add the program name to the command** - All of the executables in this activity are written in Bash. `bash plum`

Go forth and explore!

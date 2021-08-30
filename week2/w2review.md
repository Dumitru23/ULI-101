Week 2 review
Instructions:
The following questions are similar to those you may find on the midterm and final.
It is intended that you complete the questions without first creating the tree and then experimenting with it, since you will not have such opportunity during the tests.
Open this exercise in VI and type your answers in the space provided.
Do not check your answers until you have attempted all questions.
Use the following tree for each question.
Each question is independent of the others.
Regular files have names beginning with f, e.g. f1 etc. All other items are directories.

.
└── week2
    ├── blue
    │   ├── black
    │   └── green
    │       └── red
    │           └── f1
    ├── purple
    │   ├── f3
    │   └── white
    └── yellow
        └── red
            └── f2

Your pwd is week2 for the following questions:
1.
What is the command to make a new directory structure orange/green/pink?
mkdir -p orange/green/pink 

2.
What is the command to copy the file f1 to the white directory?
cp blue/green/red/f1 purple/white

3.
What is the command to change the name of f2 to file2 and keep it in the same place?

mv yellow/red/f2 yellow/red/file2
4.
What is the command to copy yellow and all of its contents to black?
cp -r yellow blue/black

Your pwd is green for the following questions:
5.
What is the command to copy f1 to white and change its name to file1 and the same time?
cp red/f1 ../../purple/white/file1

6.
What is the command to rename f3 to file3 and move it to the pwd, all in one command?
../../purple/f3 ./file3

7.
What is the command to copy f1 to the week2 directory?

cp red/f1 ../..


 

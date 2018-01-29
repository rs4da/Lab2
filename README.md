# Lab2
CS 3240 Lab 2 - Roman Sharykin (rs4da)

Activity 3: 

            link to fork - https://github.com/rs4da/Lab2Fork-102
            
            link to pull request - https://github.com/UVA-CS3240-S18/Lab2Fork-102/pull/22
            
            improvement 1: Originaly pig.py was checking the condition "while not done" twice, once at the every start of the program and once again alongside the check for whose turn it currently is. Since checking the same condition twice is clearly pointless I removed it. 
            
            improvement 2: In lo_shu.py I added a while loop that would check if the amount of numbers passed in by the user was correct (equal to 9), and if the user entered a different amount the program would continue to prompt him/her until the number entered is correct. I think this improvement is needed since without it the program just throws an error and quits, without specifialy telling the user what's wrong. My tweek just makes the program a little more user friendly.  

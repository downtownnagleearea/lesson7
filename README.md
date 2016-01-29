# Lesson 7 Do codecademy 'Getting Started'

## Fork this lesson
1. Select the fork button in the upper right of this page that looks like the following: 
![screen shot 2016-01-27 at 1 13 09 pm](https://cloud.githubusercontent.com/assets/146453/12629289/149c3ec2-c4fc-11e5-9446-10f3021af8a7.png)
2. Fork this lesson to your github home
3. Now you should see lesson7 in your github home - eg `https://github.com/<you>/lesson7`

## ssh into your edison board to you can start this lesson
1. Go to https://developer.weaved.com/portal/members/home.php
It will provide a ssh login similar to
ssh -l LOGIN proxya.yoics.net -p 34141
2. Bring up a terminal window and type in the command above substituting LOGIN with your name
   * example `ssh -l freddie proxya.yoics.net -p 34141`

## Clone this lesson to your edison board so you can later mark it as complete
1. Clone the forked lesson to your edison board
   * `git clone https://github.com/<you>/lesson7.git`
2. Change to this directory
   * `cd lesson7`
3. Add the original lesson7 as the upstream repo
   * `git remote add upstream https://github.com/downtownnagleearea/lesson7.git`

## Start Codecademy
1. Browse to https://www.codecademy.com/learn/javascript
2. Select 'Getting started with Javascript'
3. Go through all 28 steps to finish this lesson
4. At the end of the lesson take a screen shot similar to below

![screen shot 2016-01-27 at 8 41 39 am](https://cloud.githubusercontent.com/assets/146453/12629492/04f9b44e-c4fd-11e5-95bd-4a7dbe1c0c8f.png)


## Update lesson7 to show you're done
1. Go back to the edison board and cd to lesson7
   * `cd lesson7`
2. Create a file called with your github name as the filename
   * `touch <yourname>`
3. Add this to your local github repository
   * `git add <yourname>`
   * `git commit -a -m"done!"`
4. Push these changes back to your fork
   * `git push origin master -f`	
5. Go to the original lesson7 in your browser and create a pull request
   * `https://github.com/downtownnagleearea/lesson7`
 



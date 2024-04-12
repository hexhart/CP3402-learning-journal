# Week 9 Learning Journal <br/>

## Learning Activities & Resources
* Watching LinkedIn Video on [Sass Essential Training](https://www.linkedin.com/learning/sass-essential-training-15630917/sass-requirements?u=2223545) to gain understanding of week 9 focus topic,
* Installing Node.js, Setting up Vite and other software required for Sass to begin working on the task requirements,
* Reading the README.md file for [nodejs/node-gyp Git repository](https://github.com/nodejs/node-gyp#on-windows) to find out how to install and start using Node.js,
* Following the Getting Started guide for [Vite](https://vitejs.dev/guide/) to install Vite and understand what it is used for in this practical exercise,
* Exploring the website, [raybo.org/slides_sassesst](https://raybo.org/slides_sassesst/#/), that was mentioned in the LindkedIn video. 


## Estimated Hours
**Estimated hours**: 4 Hours

## Content Insights
* LinkedIn Video Insight: 
  - To be posted later after draft is completed


* Installing software required for the task: 
  - Node.js installed using installers for windows,
  - Create the project structure/directory,
  - Create the necessary files .scss, .html, most importantly gulpfile.js, adding content to package.json,
    - After file creation, run 'npm install' in the project directory to install the Gulp and the plugins,
    - Run command 'npm run gulp' to compile Sass and see the changes in the terminal,
  - Use command 'npm init -y' to initialize the new npm project, this creates the package.json file,
  - SCSS styles are written in 'src/scss/styles.scss' and variables are defined in the '_variables.scss'.
  - Within gulpfile.js:
    - const { src, dest, watch, series, task } = require('gulp');
      - This code imports the functions from the gulp package,
      - src gets the source files that needed to be manipulated,
      - dest to output the manipulated files,
      - watch to watch the file changes,
      - series to execute tasks in series,
      - tasks to define a new task,
    - const sass = require('gulp-sass')(require('node-sass'));
      - this line imports the gulp-sass package and passes node-sass as the compiler.
      - gulp-sass is the Gulp plugin for compiling the sass files to CSS.
    
    

## Career/Employability/Learning Insights

### Learning about SASS<br>
  - Sass extends the functionality of CSS by allowing the use variables, nesting, mixins, and inheritance.

### Practical Insight<br>
  - Additional practical task submission at this point of the subject feels too redundant,
    - Working on this task while attempting the group assignment demands more of my time compared to other subjects,
    - While time availability was an issue, I was not able to explore more this topic hence the outcome of my deliverable submission,
  - Despite this ordeal, doing the practical task and assignment simultaneously tests my ability to:
    - work under-pressure by keeping calm and being motivated to push through,
    - work smartly through prioritization of the tasks based on their importance and deadline
  - This task allowed me to demonstrate my ability to: 
    - Become more adaptable by embracing on new methods to tackle the tasks while sticking to the deadline,
    - Focus on prioritizing tasks,
    - Overcome obstacles such as being stressed, overwhelmed and unmotivated,

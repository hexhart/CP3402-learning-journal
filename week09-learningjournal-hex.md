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
  - Understanding the two flavours of SASS (Sass and SCSS), provides clarity on the options available for writing the stylesheet,
  - Learning about the SASS syntax reveals the difference in approach between the indented format of SASS and the more familiar SCSS formatting,
  - Realizing that SASS eliminates a lot of punctuation, making it feel more lightweight and intuitive, benefits from writing cleaner codes,
  - Identifying that SCSS maintains full compatibility with CSS,
    - it facilitates seamless integration of existing CSS code which can be appealing to developers who aim for ease of migration and maintainability,
  - Variables in SASS provide a way to create a placeholder for values which allows me to efficiently manage and use styles,
  - SASS variables are:
    - Usually written with a dollar sign followed by the variable name, similar to CSS properly declarations, but with added functionlity to use expressions and formulas,
    - It is always converted to CSS during compilation which reduces the CSS output,
    - It typically has a global scope which makes it accessible throughout the stylesheet and it can also be defined locally within curly braces of a specific code block(S),
  - Mixins feels similar to JavaScript functions, which makes styling flow more efficient,
  - Using @mixin rules to define a mixin, followed by a name and optional arguments, this also includes the default values if required.
    - It can be called using the @include at-rule,
    - This can be done with specific parameter values or without passing any values,
  - Always use descriptive names that accurately reflect their purpose and function for readability and maintenance of code,
  - Be careful when using mixin as this has performance implications such as generating large amount of CSS output.
    - Optimize mixins by generating minimal CSS output, avoiding unecessary properties or declarations,
    - Use placeholder selectors (%selector) instead of classes or IDs within the mixins,
    - Limit nesting within mixins.

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
  - index.html is where to view the Sass website,
  - Use command 'npm cache clean --force' when encountering Corrupted npm cache,
    

## Career/Employability/Learning Insights

### Learning about SASS<br>
  - This practical exercise enabled me to improve the way I write my CSS code by allowing to:
    - organize the variables, nesting, mixins, and inheritance in separate files,
    - these separate files are placed into a more structured directory,
  - Despite the advantage of using Sass, I found out that there are limitations which include:
    - the difficulty to compile the Sass into the standard CSS adds complexity in the development workflow,
    - the learning curve to get familiarized with the syntax was steep,
    - Sass files size can become large, and it becomes very unmanageable if not organized properly,
  - Familiarity with Sass is required in the IT industry, hence this is an advantage for me when working with web development projects,
  - Possessing this skill ensures that I remain competitive in the job market as learning Sass demonstrates my commitment to professional growth and staying updated with industry trends and best practices in web development.


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
    

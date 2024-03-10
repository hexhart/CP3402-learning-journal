# Week 5 Learning Journal <br/>

## Learning Activities & Resources
* Personal practical task by testing imports and exports of WordPress backups,
  * Exporting backup from production and importing backup files to local environment,
  * To validate assumptions on whether backup copies of the site creates a full copy of the website's content,
  * To get familiarized with backing up the website,
* Reading online guides and instructions while attempting to create the Child Themes as part of this week's practical task,
  * Learn about working with [Child themes](https://developer.wordpress.org/themes/advanced-topics/child-themes/) and modifying WordPress themes without affecting the parent theme,
  * Understand more on developing websites with custom CSS over an existing theme or building it from scratch,
* Watching the LinkedIn Videos [WordPress: Building Child Themes](https://www.linkedin.com/learning/wordpress-building-child-themes-3/what-you-need-to-know?autoSkip=true&resume=false&u=2223545) to understand and gain insight on building Child Themes for future WordPress projects,
* Viewing additional videos such as [Learning Responsive Web Design in the browser](https://www.linkedin.com/learning/learning-responsive-web-design-in-the-browser/welcome?u=2223545), as an additional learning materials to broaden my understanding of developing responsive websites that are viewed on different browsers or platforms.


## Estimated Hours
**Estimated hours**: 5 Hours

## Content Insights
* LinkedIn: WordPress - Building Child Themes & WordPress: Child Themes
  - Create a new directory in the "wp-content/themes" directory in WordPress,
  - Child Themes should follow their parent theme's name with the inclusion of "-child". i.e. naming "maintheme-child" from parent theme "maintheme"
  - Modify the child theme using CSS codes,
    - Achieved by creating Stylesheet, located inside the child theme directory and naming the file "style.css",
    - The "style.css" file contains the stylesheet for the child theme.
  - Adding Child Theme Information by editing the 'style.css' file and add header information at the top of the file.
    - These header information includes Theme Name, URI, Description,Author, Author URI, Template, and Version.
    - Note: The 'Template' field should contain the directory name of the parent theme.
  - Create and use 'functions.php' within the Child theme directory to inherit the parent theme's styles to the child theme.
    - Using the method of "[enqueuing the parent theme stylesheet](https://www.wpthemedetector.com/child-themes-enqueuing-the-parent-theme-stylesheet-instead-of-using-import/)" with a PHP code does the trick 
  - After inheriting the styles, Child themes can be customized to my liking by adding custom CSS styles, and template files.
  - In doing the above,creation of template files similar to parent themes directory will now be possible,
    - WordPress will use the child theme's style versions instead.
  - Activating the Child theme by going to Appearance > Themes on the WordPress admin dashboard, and clicking on Activate button located at the bottom right of the child theme.



* LinkedIn: Learning Responsive Web Design in the Browser
  - Tools suggested to use were Chrome browser and Atom Code Editor, available from atom.io,
  - I learn that responsive and mobile-first designs employs the use of Web Browser to design the web interface instead of using traditional software such as Photoshop, or Illustrators.
  - Mastering HTML and CSS techniques enables using the web browser as the design canvas to design a web interface that changes depending on certain situations that includes:
    - changing the screen width, mouse click interactions, and other interactions.
  - Using Style Tiles as a style guide to design website by placing styling elements (i.e. colours, shapes, or images) and placing them in tiles on the page.
  - Pen and Paper seems more effective in creating web layout designs than using design software applications because:
    - it is quicker to generate more ideas,
    - easier to scarp mistakes and start over,
    - mapping out the semantic structure of the html document is done instantly.
    - provides a faster way to produce wire frames to give overall idea of the site's layout.
  - Sketches are not required, but it is helpful to run through different ideas quickly.
  - CSS can be used to create interactive elements that includes:
    - changing the style of an HTML element based on certain conditions such as :hover, which change the style of an element when mose is over it,
    - adding effects to an element by providing properties like "box-shadow" for drop shadows,
    - using media queries "@media" to allow the creation of different layouts when the website is viewed using different screen sizes,
  


## Career/Employability/Learning Insights

### 1. Working with Child Themes<br>
  - I gained deeper understanding of how WordPress themes are structured through using:
    1) Template files written in PHP such as index.php, header.php, and footer.php to determine the layout and structure of the WordPress site,
    2) Stylesheets that uses CSS files to define visual appearance of the different sections of the website,
    3) PHP functions to enable adding custom functionalities, modifying functionality, of the WordPress theme,
  - These mentioned key knowledge enabled me to create and customize existing themes effectively or develop themes from scratch.
  - Child themes taught me the importance of isolating customizations from a parent theme by creating separate directories,
    - thus making it easier to update a parent theme without losing my modifications.
  - Customizing Child theme allowed the opportunity to encounter design challenges and issues, allowing me to troubleshoot, and resolve them.
    - This experience helps develop my critical thinking and troubleshooting abilities, and broaden my proficiency with using WordPress for website development.
  - Creating child theme enables me to create customized WordPress solutions that can be employed to deliver custom website that would cater to Client's specific requirements.



### 2. Creating a LinkedIn account<br>
  - This social media platform allows me to connect with other professionals in different co-hort of the IT Industry,
  - Sharing insights and interests allows me to be engaged in discussions with others that could lead to expanding my network, and also gaining new valuable skills and knowledge, allowing professional growth.
  - The account enables me to be visible to potential employers looking to hire suitable candidate to their company,
    - It also creates easily accessible portfolio where I could establish my credibility and demonstrate my expertise in specific IT field.



### 3. Personal Practice WordPress backup Import/Exports<br>
  - Being familiarized with importing and exporting WordPress backup files allows the prevention of potential data loss or accidental changes to main WordPress website page contents or templates,
  - The experience allowed me to encounter some challenges and limitation with the WordPress backup feature, particularly:
    - not being able to back up everything from the production website, when restoring backup to local the themes were not included.
    - assigning local users and production users could be confusing,
    - hyperlinks from the restored pages need to be updated locally by assigning the different page id's created.
    - Page ID from the production are assigned with a new ID when restored on the local environment.
  - This additional exercise allowed me to understand more on the import and export of WordPress backup by performing the actual backup process,
  - It also helped in validating my assumptions whether the WordPress backup feature fully or partially copies everything from production to the local environment.

# Week 4 Learning Journal <br/>

## Learning Activities & Resources
* Attending the seminar class to gather additional feedback for improvement in creating my learning journal,
* Taking notes on the feedback and reflecting on it by applying new approaches to my writing,
* Conducting research to get familiarised with the concept of Local Environment using Vagrant tool and Virtual Box,
* Reading and watching the recommended LinkedIn videos to gain better understanding on Modern Web Design processes and how it relates to CMS,
* Following installation guides and tutorials videos for both implementing my local environment using Vagrant and Varying-Vagrant-Vagrants (VVV) tools.
* Learning Resources used:
  - Study Materials:
      - [LinkedIn Video: A guide to the web design process](https://www.linkedin.com/learning/mapping-the-modern-web-design-process/a-guide-to-the-web-design-process-14881661?autoplay=true&resume=false&u=2223545)
      - [LinkedIn Video: Version Control for Everyone](https://www.linkedin.com/learning/version-control-for-everyone-2/building-a-wordpress-theme?u=2223545)
      - [LinkedIn Video: Write and commit in small chunks](https://www.linkedin.com/learning/version-control-for-everyone-2/write-and-commit-in-small-chunks?resume=false&u=2223545)
  - Practical Material:
      - [Ultimate WordPress Development Workflow by Zach Adams](https://zach-adams.com/2014/09/ultimate-wordpress-development-workflow/)
      - [Getting started with Vagrant & VVV for local development](https://webdevstudios.com/2015/01/14/getting-started-vagrant-vvv-local-development/)
      - [Install Vagrant](https://developer.hashicorp.com/vagrant/tutorials/getting-started/getting-started-install)
      - [Introduction to VVV](https://varyingvagrantvagrants.org/)
      - [How to Create Your First Contact Form](https://www.youtube.com/watch?v=o2nE1P74WxQ)
      - [WPForms: Creating First Form](https://wpforms.com/docs/creating-first-form/) 

## Estimated Hours
**Estimated hours**: 10 Hours

## Content Insights
* LinkedIn Video: A guide to the web design proces, Version Control for Everyone, Write and commit in small chunks
   - Version Control is important to manage and tracks changes made to project files that makeup the WordPress theme (for this video),
   - VC demonstrates the importance of managing large projects by keeping a record of commits made,
   - Bug tracking is easily detectable with version control,
   - Creation of branch version enables working different version of the file in the Main repository,
   - WordPress uses Subversion, a centralized remote system/server that contains the repository. 
   - Other copies are working copies that doesn't actually contain the full history. 
   - For files to contain history connecting to the server is required using Git and Git SVN command. 
   - When making commits, focus on making small commits at a time,
   - Documentation files are written in Markdown, an industry format used across platforms like GitHub,
   - Undo options are available within the editor,
   - Version control helps to revert back any changes made after closing files,
   - While editor has undo functions, it is limited to what it can do to file once it is closed and reopened.
   - Always remember to adopt systematic versioning practices when working of any software development workflows.


* Practical Reading Material 1: Ultimate WordPress Development Workflow by Zach Adams
   -  Establishing a WordPress development workflow makes it more efficient by allowing testing, deployment and collaboration,
   - Tools to explore: Git, Vagrant, Composer, WP-CLI, Grunt (not necessary all for now)
   - Git allows for version control, making it easier to track changes and collaborate with others,
   - Vagrant helps create a reproducible and portable work environment, which is important for testing and deployment my WordPress site,
   - Adopt best practices approach in WordPress development to include coding standards, backing up data and optimizing performance,
   - Using child theme allows me to modify my WordPress theme without affecting the original, this makes it easier to update and maintain,
   - Regular backups as a safety measure to protect my work from unexpected losses, Version control works too to track down changes and revert from unwanted updates,


* Practical Reading Material 2: Getting started with Vagrant & VVV for local development
  - Vagrant runs on top of a virtual machine provider (VirtualBox), enables running codes while keeping the WordPress workflow locally,
  - It is configured within the Vagrantfile,
  - VVV is a Vagrant setup that allows WordPress development in a local machine.
  - Setup instructions found via: [1](https://github.com/varying-vagrant-vagrants/vvv) and [2](https://varyingvagrantvagrants.org/docs/en-US/installation/)


* Practical Reading Material 3: Vagrant: Install Vagrant
   - Note: To install Vagrant software on local machine
   - First step is to signed up for an account using GitHub account credentials, completing this step by agreeing to the Service Agreement and clicking on "Continue"
   - On the [HashiCorp](https://developer.hashicorp.com/) homepage, click on the Vagrant shortcut button to go back to Vagrant webpage.
   - Click on Tutorials link, and select Get Started link to start setting up Vagrant.
   - Begin setting up Vagrant by downloading the installer from [Vagrant](https://developer.hashicorp.com/vagrant/install), select the appropriate installer suitable for my local machine
   - Run installer, follow through the series of steps and click "Finish" button to complete installation and Select 'No' to restart the laptop later.


* Practical Reading Material 4: Introduction to VVV ([Varying Vagrant Vagrants](https://varyingvagrantvagrants.org/docs/en-US/adding-a-new-site/)): Installation, Basic Usage, Default Sites in VVV 
   - With Vagrant and Virtual Box installed, setting up VVV needs cloning the VVV repo, moving to the cloned local directory and installing the vagrant plugin,
   - Cloning the VVV repository using the code "git clone -b stable https://github.com/Varying-Vagrant-Vagrants/VVV.git %systemdrive%%homepath%/Desktop/bb-wordpress-projects/vvv-local",
   - Move into the cloned local directory using "cd %systemdrive%%homepath%/Desktop/bb-wordpress-projects/vvv-local"
   - The CLI command %systemdrive% represents the drive where the system is installed,
   - %homepath% represents the path to current user's home directory,
   - vvv-local is the directory path or folder name for the local environment,
   - "vagrant up" starts and provisions the virtual machine according to the Vagrant file specification.
   - "vagrant halt" shuts down the virtual machine of the local environment,
   - "vagrant reload" restarts the virtual machine.
   - To test domain for local web development environment, the link is [http://vvv.test](http://vvv.test)
   - Accessing the default local hosted site through: [http://one.wordpress.test](http://one.wordpress.test)
   - Editing the local site, the link would be: [http://one.wordpress.test/wp-admin/](http://one.wordpress.test/wp-admin/)
   - Customise the local test site by accessing www/wordpress-one/public_html/wp-content folder
   - VVV’s config, database, log and www directories are shared with the virtualized server.


* YouTube Video & Web Article: How to Create Your First Contact Form & Creating Your First Form
   - Hover mouse to WPForms on the WordPress Dashboard and select Add New to add forms,
   - Select a Template or Black Form to begin designing a custom form for the website,
   - On the left pane under Add Fields tab consists of elements to be added to the Form template canvass on the right pane
   - The Field Options tab is for customizing the Field Elements.
   - Advanced options to customize the field elements further customize the Field Elements.
   - General Setting has options to include Captha and other security options (to be explored later)


## Career/Employability/Learning Insights

### 1. Installing and Setting up the Local Development Environment for WordPress using Vagrant and VVV:
  - I gained practical experience after completing this task, 
  - The experience made me realize the importance of isolating WordPress site development by having a clone of the production environment which enables me to deploy tests, changes and updates safely without affecting the live production environment.
  - The troubleshooting involved during the installation process provided me the opportunity to enhance my problem-solving abilities and also solidified my understanding of system interactions. 
  - Having a local environment allows flexibility in developing the WordPress site without worrying about the cost and risk when testing out new things, thus improving my confidence in using CMS to develop websites. 
  - Being proficient in installing and managing local development environments is a valuable skill that enhances my employability by demonstrating technical competency, productivity, collaborative skills, adaptability, and problem-solving skills.


### 2. Use of CMS Plugin: WP Form Experience: <br>
  - Using CMS plugins made me realize how flexible CMS systems by the way it enables customization that caters to our needs and also meeting customer requirements,
  - CMS plugins expands the core functionalities of my website without the need to do extensive coding, unlike the traditional way of developing websites without CMS systems,
  - Understanding how plugins can be configured, installed and integrated, I gain the ability to adapt CMS systems to meet unique website content requirements,
  - Learning to leverage the use of CMS plugins has helped me develop my website more efficiently by seamlessly integrating additional functionality to my website such as adding forms or adding new editors to make it easy to develop websites. 
  - Experimenting on various plugins through Trial and Error help me identify which plugins to be used for my website projects that has specific requirements.


### 3. Version Control Insights <br>
  - Realize that Version Control facilitates collaboration by allowing multiple team to work on the same project simultaneously,
  - VC enables effective collaboration that enables teams to foster shared responsibility and teamwork,
  - Learning to maintain version control helps develop to understand the history of a project changes, aids troubleshooting and understand project development,
  - It also encourages learning through code reviews allowing improvement of code quality, and promote best coding practices,
  - Proficiency in Version Control enhances my credibility as an IT professional as it signifies strong collaborative skills, attention to details and adhering to best practices,
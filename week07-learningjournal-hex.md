# Week 7 Learning Journal <br/>

## Learning Activities & Resources
* Reading [Modern PHP Crash Course](https://dev.to/ericchapman/modern-php-crash-course-3606) to learn basic PHP quickly.
* Attempting GitHub and Discord integration using [GitHub WebHook Tutorial](https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22)
* Watching parts of [Learning PHP](https://www.linkedin.com/learning/learning-php-4/should-you-learn-php?u=2223545) and [PHP with MySQL Essential Training](https://www.linkedin.com/learning/php-with-mysql-essential-training-1-the-basics/php-with-mysql-essential-training-the-basics?resume=false&u=2223545) LinkedIn Videos. 
* Following the Guide [A Site With a wp-content Git Repo](https://varyingvagrantvagrants.org/docs/en-US/adding-a-new-site/#empty-custom-site) to set up my local development environment an existing Vagrant installation for the group assignment group.

## Estimated Hours
**Estimated hours**:  5 Hours

## Content Insights
* Modern PHP Crash Course:
  - Using command: $ php -v verifies the PHP installation version,
  - Setting up a project directory and creating PHP files are done using Visual Studio Code,
  - When writing PHP code in a PHP file, the opening tag '<?php' denotes PHP code blocks,
  - 'echo' denotes basic string output, displays text or variables on a web page,
  - variables are denoted by using the dollar sign ($) followed by the variable name,
  - Variables in PHP are case-sensitive, 
  - Follow coding standards and conventions, such as PSR standards, for consistency and readability,
  - Use meaningful variable names and comments to make your code self-explanatory,
  - Break down complex tasks into smaller functions or methods to improve code maintainability,
  - Avoid deeply nested code structures to enhance readability and reduce complexity,
  

* GitHub WebHook Tutorial for GitHub and Discord: 
  - Ensure to have admin rights to the discord group, 
  - On the discord channel option, select Integrations and select Webhook,
  - Click on New Webhook, add a custom Name, select the Channel and copy the WebHook URL,
  - On GitHub repository, select settings and click on Webhooks,
    - In webhook page, click Add webhook button,
    - In Payload URL field, paste the WebHook URL and ensure to add /github to the last line,
    - Content type, select application/json,
    - Ensure that SSL verification is disabled,
    - For the event to trigger webhook, select "Send me everything" option,
    - Before clicking on "Add webhook", ensure Active box is ticked.


* Learning PHP:
   - Setting up a constant (WWW_ROOT) to define the web root 
     - Utilizing this web root to generate URLs for links and assets.
   - creating functions are usually coded in a separate PHP file ('functions.php'),
     - For instance, function such as 'url_for' inside functions.php file simplifies URL generation and this ensures consistency,
   - Four principal reserved characters in HTML - <, >, &, and ", are highlighted as points of concern, particularly < and > which signify HTML tag boundaries,
     - Poses unintended formatting or security vulnerabilities such as cross-site scripting attacks,
     - Using 'htmlspecialchars()'function encodes special characters, previously mentioned, into harmless equivalents,
   - header() function allow modification of HTTP headers,
     - LinkedIn video demonstrated how to change the content type, respond with error messages and perform advanced tasks,
   - For header modifications, headers must be set before any content is outputted, this includes whitespace or line returns.
     - this is to avoid premature output.
   - 


* Setting up local environment for the Group Assignment : 
  - In Command Prompt, move to the project folder where the existing vvv-local folder is located,
  - Use 'vagrant up' to start the virtual machine,
  - 'vagrant status' command is used to check the status of the virtual machine,
  - Adding the local environment of the Group Assignment to the current Vagrant,
    - Edit the YAML file and follow the code below:
    -   u3a-local:
    - skip_provisioning: false
    - description: "A standard WP install, useful for building plugins, testing things, etc"
    - repo: https://github.com/Varying-Vagrant-Vagrants/custom-site-template.git
    - php: 8.2 # change the PHP version to use for the provision and nginx
    - hosts:
      - u3a.test
    - custom:
      - wpconfig_constants:
        - WP_DEBUG: true
        - WP_DEBUG_LOG: true
        - WP_DISABLE_FATAL_ERROR_HANDLER: true # To disable in WP 5.2 the FER mode
  - After saving this code in the config.yml, go to Command Prompt and use the commant "vagrant provision" to install the new local environment for the group project U3A website. 


## Career/Employability/Learning Insights

### 1. GitHub Discord Automated Notification Integration<br>
  - I integrated this acquired skill in another discord group for another assignment for the purpose of:
    - Experimenting and learning how to automate updates on git changes made when members update the Git repository,
    - To enhance version control handling and monitoring,
    - To be proficient in managing group projects,
  - Integrating WebHooks was pretty straight forward to integrate between the two applications,
  - Only limitation in integrating this tool is that you need to have Admin privileges for both applications or else this integration may not work,
  - Some previous updates before integrating WebHook were not carried to the git-changes channel. 
    - Only the most recent Commits are pushed.
  - Learning about WebHook integration enables me the possibility to allow my web applications to interact with other platforms and services,
    - This enhances my adaptability in using modern tools and services,
    - and integrating them to improve efficiency and productivity in a team collaboration.


### 2. Learning PHP code: Modify Headers Insight<br>
  - HTTP headers play a crucial role in web communication, 
    - providing essential metadata about the content being served.
  - PHP's header() function allows developers to modify HTTP headers dynamically, 
    - enabling tasks like error handling and content type specification.
  - Headers must be set before any content is outputted, 
    - requiring careful management to avoid inadvertent output that can interfere with header modification.
  - Since I am tasked with designing the website header for U3A project, studying more on modifying headers with PHP is crucial in implementing the proposed designed website Header with it's NavBar,




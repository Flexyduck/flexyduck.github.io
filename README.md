<h2 align = "center"> How to host and format a resume on GitHub Pages </h2 >

Purpose: This README will describe the practical steps of how to host and format a resume using GitHub Pages

### Table of Contents
* [What is GitHub?](#what-is-github)
* [GitHub Pages](#github-pages)
* [What is Jekyll](#what-is-jekyll)
* [Hosting Your Resume on GitHub Pages](#hosting-your-resume-on-github-pages)
    1. [Finding a template for your resume from Jekyll](#finding-a-template-for-your-resume-from-jekyll)
    2. [Forking the repository](#forking-the-repository)
    3. [Hosting your site on GitHub Pages](#hosting-your-resume-on-github-pages)
    4. [Finding the template file for formatting your resume](#finding-a-template-for-your-resume-from-jekyll)
    5. [Using a Text Editor and Version Control Software](#using-a-text-editor-and-version-control-software)
    6. [Cloning your repository](#cloning-your-repository)
    7. [Formatting your Resume](#formatting-your-resume)
* [Authors and Acknowledgements](#authors-and-acknowledgements)
* [More Resources](#more-resources)
* [Frequently Asked Questions (FAQs)](#frequently-asked-questions-faqs)

Hosting your resume online is the first step into entering a new job market with new job opportunities in technology. GitHub is a great website to host this new resume as it is a popular name in the tech community for acquiring talent, looking up developer's portfolios and storing projects, alongside your resume makes GitHub a one-stop-shop all your tech profile and hosting your resume on GitHub is the first item you are displaying in your "shop". This ReadMe will describe the practical steps of how to host and format a resume using GitHub Pages but before we begin the tutorial on how to host a resume, we first ask:

### <ins> What is GitHub? </ins>

GitHub is a software and cloud-based service that gives users the ability to store code online, manage code, collaborate with others on code and track and record any changes to such code. GitHub is also home many documentations and even gives users the ability to stylize documentation as webpages when partnered with their sister website: *GitHub Pages*

### <ins> GitHub Pages </ins>
*GitHub Pages* is a tool from GitHub that helps you turn your GitHub repositories into webpages for better presentation and access. *GitHub Pages* gives you the ability to showcase stylish webpages for a variety of functions such as:
* Portfolios
* Projects
* Project Documentation
* Resumes

*GitHub Pages* has the added benefit of not requiring knowledge of databases, servers or, at times, knowledge of HTML. This is accomplished with the aid of static site generators like *Jekyll*

### <ins> What is Jekyll? </ins>
Jekyll is a *static site generator* that transforms your plain text file into static websites that can be editted and viewed. It allows you to change *lightweight markup languages* into elegant webpages with the help of layouts. 

 # <h4 align = "center"> <ins> Hosting Your Resume on GitHub Pages With the Help of Jekyll</ins> </h4>

1. ##### Finding a template for your resume from Jekyll
    - First, let's pick a resume template from Jekyll. Templates and themes are available from [here](https://jekyll-themes.com). You can narrow your selecting *Resumes* from the categories option on the left panel. ![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/categories.png)![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/Resumes.png) 
    <br>We selected [Online Cv](https://jekyll-themes.com/online-cv/) by Sharu725 then select **Repository** from the options ![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/repository.gif). 
    <br> This will take you to the GitHub repository for that template.

2. ##### Forking the repository
    - At this point, we will be forking this repository to our account. Log in (or [create an account](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)) and then click **Fork** from the top right. ![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/fork.png) 
    <br>After you fork the above repository to your account and give it a name. For this example, we will name our repository "Resume". You can add a description if you wish but that is optional. Finally, click **Create fork** at the bottom of the screen and you should be redirected to the forked repository named *"Resume"*.

3. ##### Hosting your site on GitHub Pages
    - In your new repository, at the top of the screen but below the repository description select **Settings**. ![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/Settings.png)
    <br> This will redirect you to the settings for the repository. In the settings page, at the left panel, select *Pages* from the *Code and automation*. When the page loads, under *Build and deployment - Source*, select *Deploy from a branch*. Then under *Branch* select the branch that currently hosts our forked repository and folder */(root)*. You can add a custom domain if you please but not necessary. You can view your newly generated site on GitHub Pages from the URL: `https://<username>.github.io/Resume`.

4. ##### Finding the template file for formatting your resume
    - This part is a bit tricky. Depending on your template chosen from Jekyll, the file that hosts the editable data to which you fill in your information varies. It is usually found in the _config.yml or data.yml file. In this case, it is the data.yml. To properly edit this .yml file you will need a couple of things:
        1. A Text Editor and 
        2. A version control software 

5.  ##### Using a Text Editor and Version Control Software
    Fire up your favourite text editor. I personally prefer just using [Microsoft Visual Studio](https://visualstudio.microsoft.com/downloads/). A version control software would also be needed to sync your changes locally to your online repository. GitHub has its own version control software called [GitHub Desktop](https://desktop.github.com). You can use GitHub Desktop and your preferred text editor to format your .yml file to match your resume. To use GitHub Desktop, you will need to clone your repository.
 
 6. ##### Cloning your repository
    - A **Set up in Desktop** option should be on the repository homepage on GitHub.
    ![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/setupindesktop.png ).This should redirect you to the GitHub Desktop app (download if necessary), and when it does, save the project. If the GitHub Desktop app does not automatically redirect, manually launch it and then just clone the repository by selecting *Clone Repository* from the File option in the Menu Bar on the top of your screen. 
    <br>![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/clone%20repository.gif) 
    - These can also be done in terminal or Command Prompt; you can clone our repository by entering <br>`git clone https://github.com/username/username.github.io` <br> into your terminal
    
7. ##### Formatting your Resume
    Your resume would need to formatted in markdown before proceeding. Markdown is a lightweight markup language that helps display your resume on web pages. A link for tutorials on formatting documents in markdown is available in the [More Resources](#more-resources) part of the document. You can edit all the template information (changing "Alan Doe" to your name etc.) and when you're done, you can upload an image of yourself as well to the /assets/images directory and change the template field *avatar* to the name of your new image file. You can also edit the color of this particular template by changing *theme-skin* option from the __config.yml file. From your Version control software, commit these changes, label this commit (for example, "Changes made to data.yml") and push them to your repository. 

 At this point, your resume should look like: ![](https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/resume.gif)

* If it does not look like this, check the [FAQs](#frequently-asked-questions-faqs) if there is anything there that helps
* If it does **CONGRATULATIONS**! you have officially hosted your resume on GitHub pages and are ready to take the tech world by storm. We wish you all the best.
### Authors and Acknowledgements
I, Tirenioluwa Biodun-Kuti (Author), would like to thank Andrew Etter for the knowledge I acquired from his book *Modern Technical Writing*, my group members  Meenal Bhatia, Maxim Omelchenko and Yee Tsung Kao for their contribution in proof reading and would also like to thank Sharath Kumar for his resume template used in this demo. 

Sharath Kumar's online-cv repository: [https://github.com/sharu725/online-cv](https://github.com/sharu725/online-cv)


### More Resources
* [Andrew Etter's Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Markdown Tutorial]( https://www.markdowntutorial.com)
* [What is GitHub Pages?](https://youtu.be/2MsN8gpT6jY)

### Frequently Asked Questions (FAQs)
1. Why is Markdown better than a word processor?
    > Markdown has some benefits over word processors namely:
        - Markdown is quite straightforward regarding editing
        - Markdown is more suited to work on browsers and online formats
        - Markdown's format has fewer distracting elements on the screen  

2. Why is my resume not showing up?
    > A number of reasons exist why your resume might not be showing up right now, like:
        - GitHub servers might be down at the moment
        - GitHub Pages mght not have been set up for your repository [click here](#hosting-your-site-on-github-pages)
        - It takes time (~3 mins) for GitHub Pages to configure your website





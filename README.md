<h2 align = "center"> How to host and format a resume on GitHub Pages </h2 >

Purpose: This README will describe the practical steps of how to host and format a resume using GitHub Pages

### Table of Contents
* [What is GitHub?](#what-is-github)
* [GitHub Pages](#github-pages)
* [Hosting Your Resume on GitHub Pages](#hosting-your-resume-on-github-pages)
    1. [Creating a GitHub Repository](#creating-a-github-repository)
    2. [Cloning Your Repository](#cloning-your-repository)
    3. [Uploading Your Resume](#uploading-your-resume)
* [Authors and Acknowledgements](#authors-and-acknowledgements)
* [More Resources](#more-resources)
* [Frequently Asked Questions (FAQs)](#frequently-asked-questions-faqs)

Hosting your resume online is the first step into entering a new job market with new job opportunities in technology. GitHub is a great website to host this new resume as it is a popular name in the tech community for acquiring talent, looking up developer's portfolios and storing projects, alongside your resume makes GitHub a one-stop-shop all your tech profile and hosting your resume on GitHub is the first item you are displaying in your "shop". This ReadMe will describe the practical steps of how to host and format a resume using GitHub Pages but before we begin the tutorial on how to host a resume, we first ask:

### <ins> **What is GitHub?** </ins>

GitHub is a software and cloud-based service that gives users the ability to store code online, manage code, collaborate with others on code and track and record any changes to such code. GitHub is also home many documentations and even gives users the ability to stylize documentation as webpages when partnered with their sister website: *GitHub Pages*

### <ins> **GitHub Pages** </ins>
*GitHub Pages* is a tool from GitHub that helps you turn your GitHub repositories into webpages for better presentation and access. *GitHub Pages* gives you the ability to showcase stylish webpages for a variety of functions such as:
* Portfolios
* Projects
* Project Documentation
* Resumes

*GitHub Pages* has the added benefit of not requiring knowledge of databases, servers or, at times, knowledge of HTML. This is all the information we need to host our resumes on GitHub Pages.

 # <h4 align = "center"> <ins> Hosting Your Resume on GitHub Pages </ins> </h4>

1. ##### **Creating a GitHub Repository**
    - Head over to [GitHub](https://github.com/), log in (or [create an account](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)), look to the **+** sign at the top right and click **New Repository** ![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/new_repository.gif)

2. ##### **Cloning your repository**
    - If you are using GitHub Desktop, you can choose the **Set up in Desktop** option ![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/setupindesktop.png ) on the repository homepage from GitHub. This should redirect you to the GitHub Desktop app, and when it does, save the project. If the GitHub Desktop app does not automatically redirect, manually launch it and then just clone the repository by selecting *Clone Repository* from the File option in the Menu Bar on the top of your screen. 
    <br>![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/clone%20repository.gif) 
    - If you are using terminal or Command Prompt, you can clone our repository by entering <br>`git clone https://github.com/username/username.github.io` <br> into your terminal.

3. #### Configuring your input.html file
    - **CONGRATULATIONS**! You have now officially created your own GitHub repository, the next step is confguring your index.html file. Since this is functionally our "Initial commit" you can create a basic index .html file. A template of a basic index.html is below.
    <br> ![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/basic_inex.png) 
    Then after configuring this index.html, we then upload it to our repository.
         - To do this, if you are using **GitHub Desktop**, save your Markdown Resume to your new cloned repository's local directory, then label this your resume as *Initial Commit* in the GitHub App and then "Push" this commit to your repository. ![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/initialcommit.gif )
        - If you are using **command line** (Terminal or Command Prompt), navigate to your directory where the resume is stored (preferably a new one), and initialize that directory as a GitHub repository by inputting:
        <br> `git init -b main`
        After you do that then, you commit the directory to repository and label that commit as *Initial Commit* then "Push" these commits to your repository. You can do this by inputting the folowing into the command line: 
         <br> `git add . && git commit -m "initial commit"`   


4. ##### **Uploading your Resume**
    - **CONGRATULATIONS**! You have now officially created your own GitHub repository, now it is time for you to upload your resume. The next step is formatting your resume in Markdown. Markdown is a lightweight markup language that helps display your resume on web pages. A link for tutorials on formatting documents in markdown is available in the [More Resources](#more-resources) part of the document. 
    <br> After you have formatted your resume into a .md (Markdown) format, next is to upload your resume to your GitHub repository.
        - To do this, if you are using **GitHub Desktop**, save your Markdown Resume to your new cloned repository's local directory, then label this your resume as *Initial Commit* in the GitHub App and then "Push" this commit to your repository. ![]( https://github.com/Flexyduck/flexyduck.github.io/blob/main/Gifs/initialcommit.gif )
        - If you are using **command line** (Terminal or Command Prompt), navigate to your directory where the resume is stored (preferably a new one), and initialize that directory as a GitHub repository by inputting:
        <br> `git init -b main`
        After you do that then, you commit the directory to repository and label that commit as *Initial Commit* then "Push" these commits to your repository. You can do this by inputting the folowing into the command line: 
         <br> `git add . && git commit -m "initial commit"`


Now you have officially hosted your resume on GitHub pages and are ready to take the tech world by storm. We wish you all the best.

### Authors and Acknowledgements
* Tirenioluwa Biodun-Kuti
* Andrew Etter
* Meenal Bhatia 
* Maxim Omelchenko 
* Stewart Wilcox
* Yee Tsung Kao 

### More Resources
* [Andrew Etter's Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Markdown Tutorial]( https://www.markdowntutorial.com)
* [What is GitHub Pages?](https://youtu.be/2MsN8gpT6jY)

### Frequently Asked Questions (FAQs)
1. Why id Markdown better than a word processor?
    * Markdown is  quite straighforwards in regards to editing
    * Markdown is more suited to work on browsers and online formats
    * Markdown's format has less distracting elements on screen  

2. Why is my resume not showing up?
    * GitHub server's might be down
    * Have you configured your index.html file?
    * Have you set up GitHub pages for your repository?
    * It takes time for (~3 mins) for GitHub Pages to configure your website



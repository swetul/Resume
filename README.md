# **Create and Host a Resume With GitHub**
For this project you will need a few basic tools to successfully **create and host a resume** on the internet. Some of the tools include **Atom (a text editor), Jekyll(static site generator)** and **GitHub(software development host)**. Read more below to see how to use these tools to complete the project.

## **Getting started**
The instructions below will help you with how the project can be successfully implemented. See Resume Tips for tips on how to make your resume attractive.

### **Intended Audience**
Ideally, this README is to help people who would like to host their resume online but have limited or no experience in tools such as GitHub, Atom, Markdown and Jekyll. Below will be all the information you will need to successfully complete this project.

### **Prerequisites**
Here are a few things you will need to do before you start this project.
1. You will need a general understanding on how to write your resume using markdown, complete the following tutorial on how to [write using markdown](https://guides.GitHub.com/features/mastering-markdown/ "GitHub flavored markdown") or [learn the basic syntax](https://www.markdownguide.org/basic-syntax/) for markdown.
2. You will need to create a [GitHub account](https://GitHub.com/join?source=header-home "create an account") to host this project.
3. You can use the online GitHub editor to create your resume but I recommend you download [Atom](https://GitHub.com/atom/atom/releases/tag/v1.41.0 "Atom download"), a text editor, see installation for how to install and notes.

### **Resume tips**
Resumes can be a complicated document to create, below are some links that can help you create, modify or get general tips on resumes.
* Resume guidelines from [University of Manitoba](https://umanitoba.ca/student/careerservices/media/Resume.pdf)
* How to improve your resume to suit ATS filtering, https://www.linkedin.com/pulse/ats-resumes-fact-fiction-adrienne-tom-cerm-mcrs/
* Or, download existing [markdown resume templates](https://mszep.GitHub.io/pandoc_resume/) to use instead.

### **Installation**
After downloading the appropriate zip file that is compatible with your computer, follow the general steps below to install Atom.
1. Open the file location where the downloaded zip file is.
2. Unzip the folder to get access to the files.
3. After unzipping the folder, look for AtomSetup.exe and double click to run the installer.
4. Once the installation is complete, close the installer and open Atom.

### **Instructions**
You do not need to make any configuration changes to be able to use Atom for creating your resume. Follow the steps below to create and publish the resume.

#### Step 1 - Creating and maintaining a GitHub repository.

  1. **Login** to your GitHub account and click on [![NEW](https://github.com/swetul/C3040_A2/blob/master/IMG/new-png.PNG)](#)

  2. Name your repository in the following format,** _username.github.io_**, where _username_ is the username of your account.
   [![NEW](https://github.com/swetul/C3040_A2/blob/master/IMG/create-rep.PNG)](#)

  3. Put in a description if you wish so, make sure to keep the repository **public**
  
  4. Select the check box with the title "Initialize this repository with a README" and click on [![NEW](https://github.com/swetul/C3040_A2/blob/master/IMG/repository.PNG)](#).
   [![NEW](https://github.com/swetul/C3040_A2/blob/master/IMG/create-public.PNG)](#)

  5. If you decided earlier to use the GitHub editor, then click on "create new file" and name it "index.md", type your resume and commit new file at the bottom of the page. Click on preview changes to see a version of your final file. Skip to part 4 if you selected this option.

#### Step 2 - Create a resume in Atom text editor

  1. Open the Atom text editor and click on "file", under file select "New File".
   [![NEW](https://github.com/swetul/C3040_A2/blob/master/IMG/atom-new.PNG)](#)

  2. Select File and click on save, name the file "index.md".

  3. Type your resume into Atom, remember in markdown format. To preview your document hit ctrl-shift-m.

  4. Finally save the file and create a new file and name it "README.md", if you want to provide any useful comments or remarks for people who will view your project, put this information in the new file.
  5. Save both files.

#### Step 3. Upload your files to GitHub.

  1. Select the repository created in step 1.

  2. Click on upload files, then drag and drop the files from your computer to the repository and select commit changes.
   [![new](https://github.com/swetul/C3040_A2/blob/master/IMG/panel-1.PNG)](#)

#### Step 4. Changing the theme on the resume

  1. Select the [![new](https://github.com/swetul/C3040_A2/blob/master/IMG/settings-1.PNG)](#) option on your repository.

  2. Scroll down to the GitHub pages section and choose "**source to master branch**".
    [![NEW](https://github.com/swetul/C3040_A2/blob/master/IMG/pages-git.PNG)](#)

  3. Click on **"change theme"** and once the page opens select a theme that you like and click select theme.

  4. Scroll back down to the GitHub Pages section and click on the **auto-generated link of your site** to view your resume site or simply type, **_https: //username.github.io_**, where username is your username, in the browser to get to the site.

  5. If you'd like to have a custom domain name for you site, return back to the **GitHub Pages section in settings** and click on the **custom domain box** and enter your custom domain name and hit **save**.

#### Step 5. Making changes to the Jekyll theme (optional)
If you wish to edit a few aspects of the theme follow the steps below.
  1. Open the __config.yml__ file in your repository and elements that you would like to add, for example to add a title, type "Title: my new title"
  2. You can also instead **fork a Jekyll theme** that you found in someone's repository, to do so open thier repsitory and click on "fork" and then submit changes to import their theme.

#### **Troubleshooting and Tips**

There can be a few places where you might find yourself stuck with a problem that you cannot find a solution to. Here are a few issues I faced myself and how to go about them.
* Issues with the links of your site. This would mainly occur if you have not selected the correct branch to Host in the settings, or your repository is private, for free Hosts the repository needs to be public.
* if you are facing issues with markdown, try looking at the prerequisites notes to find tutorials on how to write in markdown.

#### **More Resources**

| Topic                          | Links                                                                            |
| -------------                  |:-------------:                                                                   |
| Getting Started With Atom      | https://www.codecademy.com/articles/f1-text-editors                              |
| GitHub Support page            | https://help.github.com/en/github/working-with-github-pages/about-github-pages   |
| Extended Markdown syntax       | https://www.markdownguide.org/extended-syntax/                                   |

#### **FAQs(Frequently Asked Questions)**
Can I Host a webpage with a private repository?
* **Yes**, However the webpage is still public and can be accessed by anyone with the link.

Do I need to provide a README file?
* Generally no, but if you intend to comment on or provide some context for people viewing your webpage it is helpful to have a README file.

How can I make a custom domain to host my webpage?
* To create a custom domain, click on "settings" in your repository, then scroll down to the GitHub pages section and type the desired domain name in the "Custom domain" box and hit save.

#### **Credits and Acknowledgments**
Template theme credits -  [Matt Graham](https://twitter.com/michigangraham)

Revised and edited by **[Zelin Qui](www.github.com/Zelin-qiu)**

#### Contact information
Email me at "patels15@myumanitoba.ca" if you find any issues with this file or the project in general.

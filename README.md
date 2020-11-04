# Hosting and formatting a resume using Markdown, a Markdown editor, Github pages and Jekyll.
 
The purpose of this readme is to explain a bit about Markdown and how to use an editor to write in markdown. Then we will be discussing how we can use GitHub pages and jekyll to host an online resume. We will also discuss a bit about GitHub pages and jekyll.
 
## Prerequisites
 
To ensure that this README is understood properly and clearly the reader must :
* Have a **_resume_** written out to be referred to while creating the online resume.
* Some knowledge about **_Markdown_**.
* Knowledge about **_GitHub_**.
 
## Markdown
 
Mark down is a Markup language that is a simple, effective tool for writing and formatting text documents that will be hosted on the web. It is an alternative to HTML. Markdown is easy to learn and easy to read. It is also easily converted to many different files.
[Here](https://helloacm.com/markdown-markup-language-quick-tutorial/) you will find more in depth about how to use markdown. Markdown is so convintent that you can use tools online to convert any PDF/word file to Markdown. Follow the [link](https://word2md.com) to do so. 
 
## GitHub pages
 
Github pages is a website for projects that can be directly hosted from a GitHub repository. In other words it is a hosting service that takes HTML, CSS and JavaScript form a repository on GitHub. It is completely free to use and does not contain ads.
 
## Jekyll
 
Jekyll is a static site Generator. It uses texts from a markup language and uses layouts to create a static website. It is free to use and open source. It is also easier to use than most other site generators.
 
## How to host an online resume online:
 
1. ### Create a GitHub account.
   > * _Step1_: If not yet, please create a [GitHub](https://github.com) account.
   > * _Step2_: Create a repository on GitHub following the [link](https://pages.github.com).
2. ### Choosing a temple.
   > * _Step1_: We can choose a lot of different templates to model our resume after. For example we can use [modern-resume-theme](https://github.com/sproogen/modern-resume-theme).
   > * _Step2_: To use this template we need to download [resume-template.zip](https://github.com/sproogen/modern-resume-theme/archive/gh-pages.zip) and extract them.
3. ### Pushing the files into the GitHub repository.
   > * _Step1_: Open the GitHub repository on your browser.
   > * _Step2_: Click the **_Add file_** to bring the drop down menu.
   > * _Step3_: Then from the drop down select **_Upload files_**.    
   ![""](gif2.gif)
   > * _Step4_: -> **Option1**: Drag and drop the downloaded unzipped files from your downloads(or where you unzipped it) to the created repository.
   >
   >![""](gif1.gif)
   >
   > * _Step4_: -> **Option2**: Or click **_Choose your file_** and add the un-zipped downloaded file to your GitHub repository.
   > * _Step5_: Once satisfied with the changes click **_Commit changes_**.  
4. ### Viewing the template.
   >![""](gif3.gif)
   > * _Step1_: Now you can view the changes going to **_Settings_**.
   > * _Step2_: There will be a section under **_Settings_** called **_GitHub pages_**.
   > * _Step3_: Right on the second line of the section there will be a box with a link. This link is where you can see your published pages.
   > * _Step4_: -> **Option1**: If the box containing the link is green and it says _" Your site is published at "_ in front of the link that means the link is published and ready to be viewed.
   > * _Step4_: -> **Option2**:f the box containing the link is blue and it says _" Your site is **ready to be** published at "_ in front of the link that means the link is being published and is not ready to be viewed.
5. ### Customize and make changes to _config.yml
   > This file contains the main file to be edited and modified so that the template resume includes all the necessary information of your resume.
   > Examples : Change name, Change title, Change email, so on and so forth.
6. ### Customise the _data files
   > The **__data_** folder contains files to make changes to specific sections.
   > The **_education.yml_** contains the necessary information to make changes to the education section in the **__config.yml_** file.
   > >The following is a format for modifying the education section.
   > >```
   > >- layout: left (options: left, right, top, top-right, top-middle)
   > >name: Institution name
   > >dates: Date Range (eg. 2018 - 2022)
   > >qualification: Qualifications (eg. BSc Computer Science)
   > >quote:
   > >    Short institution or course description
   > >description: | # this will include new lines to allow paragraphs
   > >    Description of qualification
   > >```
   > The **_experince.yml_** contains the necessary informations to make changes to the experience section in the **__config.yml_** file.
   > >The following is a format for modifying the experience section.
   > >```
   > >- layout: left (options: left, right, top, top-right, top-middle)
   > >company: Company name
   > >link: Link to company (eg. https://google.com)(optional)
   > >job_title: Job title
   > >dates: Date Range (eg. November 2018 - present)
   > >quote:
   > >    Short description of the company (optional)
   > >description: | # this will include new lines to allow paragraphs
   > >    Description of role
   > >```
   > The **_Projects.yml_** contains the necessary informations to make changes to the projects section in the **__config.yml_** file.
   > >```
   > >- layout: left (options: left, right, top, top-right, top-middle)
   > >    name: Project name
   > >link: Link to project (eg. https://sproogen.github.io/modern-resume-theme)
   > >github: Github page for project (eg. sporogen/modern-resume-theme)
   > >quote:
   > >    Short overview of the project
   > >description: | # this will include new lines to allow paragraphs
   > >    Description about the work on/with the project
   > >```
7. ### Finished
   > Now once everything is edited you can commit the change and then use the link as before to view the changes.
   
## Authors and Acknowledgments

* Sheikh Shafayet Hossain
* Andrew Etter
* Aaron Salo
* Kyle Lamoureux
* Kevin Davis

## FAQs
 
1. Why is Markdown better than a word processor?
   >   
   >    Ans: Markdown can be easily converted to many other files (example HTML) unlink Word processor.
 
2. Why is my resume not showing up?
   >
   >    Ans: After a resume is published on GitHub pages it takes some time to set us and publish using the link provided under Settings > GitHub pages.
 
## More Resources
 
[Learn MarkDown](https://helloacm.com/markdown-markup-language-quick-tutorial/)</br>
[GitHub Pages](https://pages.github.com)</br>
[Modern Techbical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)


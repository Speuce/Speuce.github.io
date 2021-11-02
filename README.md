# Writing and hosting a Resumé on GitHub Pages

**Purpose:**  This document exists as a guide to hosting a resume online using Markdown, Jekyll and GitHub Pages. Additionally, this guide will relate this process to the general principles of Technical Writing as described in Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_.

## Prerequisites

In order to follow along with this guide, it is recommended that you are familiar with Markdown, and have a resume to use that is ready to be formatted in Markdown. See the [More Resources](https://github.com/Speuce/Speuce.github.io/blob/master/README.md#more-resources) section of this guide for resources on both resume writing and Markdown.

## The Guide

Following Etter's general principles of Technical Writing, these steps will guide you through the process of hosting your resume on GitHub Pages.

### Use Lightweight Markup (Markdown)   
Etter recommends using lightweight markup for modern technical writing (see: [Why Should I Use Lightweight Markup?](https://github.com/Speuce/Speuce.github.io/blob/master/README.md#why-should-i-use-lightweight-markup)). Markdown is one popular 'flavour' of lightweight markup that integrates well with GitHub.  

1. **Choose a Markdown editor to use for your resume.**
    Some options include:
      - MarkdownPad (Windows)
      - iAWriter (macOS)
      - ReTex (Linux)
2. **Format your resume in Markdown using your chosen Markdown editor**  
    - If you need help with writing Markdown, see: [More Resources – Markdown](https://github.com/Speuce/Speuce.github.io/blob/master/README.md#markdown).
    - Use headers and lists wherever it is appropriate, as suggested by Etter's book.
    - Use _italics_ for _emphasis_, as suggested by Etter's book.
3. **Save your resume as `index.md`**

### Use a Distributed Version Control System(DVCS)

Etter recommends using DVCS to manage and work on technical writing. It allows you to work on changes offline, work with others in parallel, and offers a vast number of integrations. DVCS is used in industry for both technical writing and software engineering. For this guide, GitHub and Git are suggested for DVCS. GitHub is free, publicly available, and offers free hosting of static websites via GitHub Pages.

For more information on git/GitHub see: [More Resources – Git/GitHub](https://github.com/Speuce/Speuce.github.io/blob/master/README.md#gitgithub)

1. **Create a Github Account**
    Go to [github.com/signup](https://github.com/signup) and follow the prompts.
    
2. **Create Your Repository**
    1. Click 'Create Repository' on the left-hand side
    2. Enter YourUsername.github.io in 'Repository Name'.  
        For example, for the user 'xeraxa4717':  
        <img width="509" alt="Screen Shot 2021-10-30 at 4 44 01 PM" src="https://user-images.githubusercontent.com/8062248/139559190-527bc3ec-c6b1-4e7a-a558-8e54975e3de5.png"> 
    3. Click 'Create Repository' at the bottom of the page.   
 
    **Result:** You have now created the space where your markdown resume will live, a repository.
    
3. **Upload your Markdown-Formatted Resume**
    1. Click on 'uploading an existing file', pictured below:  
            ![image showing uploading an existing file](/assets/img/img2.png)  
    2. Click on 'choose your files'.
    3. Select your 'index.md' markdown file.
    4. Click on 'Commit changes' at the bottom.  
   
    **Result:** You will now see 'index.md' listed in your repository:  
        <img width="1012" alt="Screen Shot 2021-10-30 at 4 58 59 PM" src="https://user-images.githubusercontent.com/8062248/139559477-6b652b99-e441-4d63-afd8-0286a5f4cf29.png">   

### Format with a static site Generator

Etter recommends using a static site (as opposed to a dynamic site) because of its speed, ease of use, and security. Static sites can essentially be hosted anywhere, require no external packages, and use a small amount of hardware. They are essentially just a series of HTML/CSS/JavaScript files. Etter recommends using a static site generator in order to build HTML/CSS/JavaScript from Markdown files and a provided theme. Static site generators make it easy for you to make changes to your site, without having to deal with the issues that come with HTML. For this guide, Jekyll is suggested as a static site generator. Jekyll is easy to use and run, and comes with many preexisting themes to customize the appearance of your website.

1. **Click on 'Settings' from your repository's main page**
    ![image showing settings button](/assets/img/img3.png)
2. **Click on 'Pages' on the left hand side**
3. **Click 'Choose a theme' under 'Theme Chooser'**
4. **Choose a theme from the options provided by GitHub**
5. **Click on 'Select' Theme**
6. **Click on the link in the green box 'Your site is published at ...',** as shown below:
    ![The result](/assets/img/show_page.gif) 

## Final Result
Your Markdown resumé will be visible on GitHub Pages, with the selected Jekyll theme applied. 

## Frequently Asked Questions

### Why should I use Lightweight Markup?
In his book, Andrew Etter lists a few main reasons for one to choose Lightweight Markup over other options:
  - It is completely human-readable in its raw/unprocessed form.
  - It doesn't require any specialized or expensive software.
  - It can be created using virtually any text editor, on any operating system
  - It works well with version control (unlike PDFs or Word documents)

### Can I upload my markdown resume another way?
Yes, you can:
1. Go to the home page of your repository ('github.com/yourusername/yourusername.github.io).
2. click on 'add a file'.
3. Drag and drop your markdown resume into the box.
4. Click 'commit' at the bottom of the page.

## More Resources

### Markdown
* [Getting Started - Markdown Guide](https://www.markdownguide.org/getting-started/)

### Resume Writing
* [UManitoba's Career Services Resume Workbook](https://umanitoba.ca/student/careerservices/media/Resume.pdf)

### Technical Writing
* Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_

### Git/GitHub
* [Pro Git Book – What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
* [GitHub Hello World guide](https://guides.github.com/activities/hello-world/)
    

## Acknowledgements
**Jekyll Template:** [Pudhina by knhash](https://github.com/knhash/Pudhina)

# Writing and hosting a Resumé on GitHub Pages

**Purpose:**  This document is exists as a guide to hosting a resume online using Markdown, Jekyll and GitHub Pages. Additionally, these steps will relate to the general principles of Technical Writing as descibed in Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_.

## Prerequisites

In order to follow along with this guide, it is recommended that you are familiar with Markdown, and have a resume to use that is ready to be formatted in Markdown. See the [More Resources](https://github.com/Speuce/Speuce.github.io/blob/master/README.md#more-resources) section of this guide for resources on both resume writing and Markdown.

## The Guide

Following Etter's general principles of Technical Writing, these steps will guide you through the process hosting your resume on GitHub Pages.

### Use Lightweight Markup (Markdown)   
Etter recommends using lightweight markup for modern technical writing (see: [Why Lightweight Markup?]()). Markdown is one popular 'flavour' of lightweight markup that integrates well with GitHub.  
1. **Choose a Markdown editor to use for your resume.**
    Some options include:
      - MarkdownPad (Windows)
      - iAWriter (macOS)
      - ReTex (Linux)
2. **Format your resume in Markdown using your chosen Markdown editor**  
    - If you need help with writing Markdown, see: [More resources - Markdown]().
    - Use headers and lists wherever it is appropriate, as suggested by Etter himself.
    - Use _italics_ for _emphasis_
3. **Save your resume as `index.md`**

### Use Distributed Version Control (DVCS)

Etter recommends using DVCS to manage and work on technical writing. It allows offline work, concurrent work with others, and a vast number of integrations. For this guide, GitHub is suggested for DVCS.

1. **Create a Github Account**
    Go to [github.com/signup](https://github.com/signup) and follow the prompts.
    
2. **Create Your Repository**
    1. Click 'Create Repository' on the left-hand side
    2. Enter YourUsername.github.io in 'Repository Name'. 
        For example, for the user 'xeraxa4717':  
        <img width="509" alt="Screen Shot 2021-10-30 at 4 44 01 PM" src="https://user-images.githubusercontent.com/8062248/139559190-527bc3ec-c6b1-4e7a-a558-8e54975e3de5.png">. 
    3. Click 'Create Repository' at the bottom of the page.   
 
    **Result:** You have now created the space where your markdown resume will live, a repository.
    
3. **Upload your Markdown-Formatted Resume**
    1. Click on 'uploading an existing file', pictured below:  
            ![image showing uploading an existing file](/assets/img/Screen Shot 2021-10-30 at 4.54.21 PM.png)
    2. Click on 'choose your files'.
    3. Select your 'index.md' markdown file.
    4. Click on 'Commit changes' at the bottom.  
   
    **Result:** You will now see 'index.md' listed in your repository:  
        <img width="1012" alt="Screen Shot 2021-10-30 at 4 58 59 PM" src="https://user-images.githubusercontent.com/8062248/139559477-6b652b99-e441-4d63-afd8-0286a5f4cf29.png">   

### Format with a static site Generator

Etter recommends using a static site (as opposed to a dynamic site) because of their speed, ease of use, and security. They are essentially just a series of HTML/CSS/JavaScript files. Etter recommends using a static site generator in order to build HTML/CSS/JavaScript from Markdown files and a provided theme. For this guide, Jekyll is suggested as a static site generator.

1. **Click on 'Settings' from your repository's main page**
    <img width="1044" alt="Screen Shot 2021-10-30 at 5 28 10 PM" src="https://user-images.githubusercontent.com/8062248/139560092-679d5260-af0c-416b-a39c-541398085305.png">
2. **Click on 'Pages' on the left hand side**
3. **Click 'Choose a theme' under 'Theme Chooser'**
4. **Select a theme from the options provded by GitHub**
5. **Click on 'Select' Theme**
6. **Click on the link in the green box 'Your site is published at ...',** as shown below.
    **Result:** Your resumé should be visible, with the selected theme applied. 
    ![The result](/assets/img/show_page.gif) 

## Frequently Asked Questions

### Why should I use Lightweight Markup?
In his book, Andrew Etter lists a few main reasons for one to choose Lightweight Markup over other options:
  - It is human-readable in its raw form.
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
  - [Getting Started - Markdown Guide](https://www.markdownguide.org/getting-started/)

### Resume Writing
  - [UManitoba's Career Services Resume Workbook](https://umanitoba.ca/student/careerservices/media/Resume.pdf)

### Technical Writing
  - Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_

## Acknowledgements
**Jekyll Template:** [Pudhina by knhash](https://github.com/knhash/Pudhina)

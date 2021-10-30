# Writing and hosting a Resumé on GitHub Pages

**Purpose**  
This document is exists as a guide to hosting a resume online using Markdown, Jekyll and GitHub Pages. Additionally, these steps will relate to the general principles of Technical Writing as descibed in Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_.

## Prerequisites

In order to follow along with this guide, it is recommended that you are familiar with Markdown, and have a resume to use that is ready to be formatted in Markdown. See the [More Resources](https://github.com/Speuce/Speuce.github.io/blob/master/README.md#more-resources) section of this guide for resources on both resume writing and Markdown.

## The Guide

Following Etter's general principles of Technical Writing, these steps will guide you through the process hosting your resume on GitHub Pages.

1. Use Lightweight Markup (Markdown)
Etter recommends using lightweight markup for modern technical writing (see: [Why Lightweight Markup?]()). Markdown is one popular 'flavour' of lightweight markup that integrates well with GitHub.
  1.1. **Choose a Markdown editor to use for your resume.**
      Some options include:
        - MarkdownPad (Windows)
        - iAWriter (macOS)
        - ReTex (Linux)
  1.2. **Format your resume in Markdown using your chosen Markdown editor**
      If you need help with writing Markdown, see: [More resources - Markdown]().
  1.3. **Save your resume as `index.md`**

2. Use Distributed Version Control (DVCS)

  Etter recommend using DVCS to manage and work on technical writing. It allows offline work, concurrent work with others, and a vast number of integrations. For this guide, GitHub is suggested for DVCS.
  
  2.1. **Create a Github Account**
    Go to [github.com/signup](https://github.com/signup) and follow the prompts.
  2.2. **Create Your Repository**
    2.2.1. Click 'Create Repository' on the left-hand side
    2.2.2. Enter YourUsername.github.io in 'Repository Name'
      For example, for the user 'xeraxa4717':
      <img width="509" alt="Screen Shot 2021-10-30 at 4 44 01 PM" src="https://user-images.githubusercontent.com/8062248/139559190-527bc3ec-c6b1-4e7a-a558-8e54975e3de5.png">
    2.2.3. Click 'Create Repository' at the bottom of the page.  
  **Result:** You have now created the space where your markdown resume will live, a repository.
  2.3.**Upload your Markdown-Formatted Resume**
    2.3.1. Click on 'uploading an existing file', pictured below:
    <img width="465" alt="Screen Shot 2021-10-30 at 4 54 21 PM" src="https://user-images.githubusercontent.com/8062248/139559398-0ad5360c-4a7d-431e-8b54-9fe13b614972.png">  [Can't find it?]()
    2.3.2. Click on 'choose your files'.
    2.3.3. Select your 'index.md' markdown file.
    2.3.4. Click on 'Commit changes' at the bottom.
  **Result:** You will now see 'index.md' listed in your repository:
    <img width="1012" alt="Screen Shot 2021-10-30 at 4 58 59 PM" src="https://user-images.githubusercontent.com/8062248/139559477-6b652b99-e441-4d63-afd8-0286a5f4cf29.png">
  
  


## Frequently Asked Questions

### Why Lightweight Markup?
In his book, Andrew Etter lists a few main reasons for one to choose Lightweight Markup over other options:
  - It is human-readable in its raw form.
  - It doesn't require any specialized or expensive software.
  - It can be created using virtually any text editor, on any operating system
  - It works well with version control (unlike PDFs or Word documents)

### help (TODO)

## More Resources

### Markdown
  - [Getting Started - Markdown Guide](https://www.markdownguide.org/getting-started/)

### Resume Writing
  - [UManitoba's Career Services Resume Workbook](https://umanitoba.ca/student/careerservices/media/Resume.pdf)

### Technical Writing
  - Andrew Etter's book _[Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)_

## Acknowledgements
**Jekyll Template:** [Pudhina by knhash](https://github.com/knhash/Pudhina)

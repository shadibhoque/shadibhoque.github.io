---
layout: post
---

# Hosting a Resume Online
## Purpose
This document serves as a guide on how to host a resume on online using tools such as Markdown editor, Jekyll and GitHub Pages. It also connects the principles on current Technical Writing that are presented by Andrew Etter on his book Modern Technical Writing



## Prerequisites
1. A Resume that is formatted in Markdown and tailored to the specific job requirements
2. A GitHub account and some general knowledge on how to use GitHub.



## Instructions
### Hosting your resume on a static site
We will be using GitHub pages as it allows anyone to host a public website through GitHub. It is very easy to create and is also free of cost.

1. Save your resume that is formatted in markdown in a .md file
2. Name the file ``index``.
3. Open your GitHub account and create a new public repository.
4. Make sure that the name of the repository is in the format ``username.github.io``
5. Upload your resume i.e. the ``index.md`` file
6. Set the default branch in settings to ``main``

Andrew Etter in his book exlplains in his book to write based on your audience.It is very important to know who you are writing for and what prior knowledge they may have on the subject. Here it is assumed that the user knows what GitHub is but does not know how to navigate through it. He mentions it is also important to give a desciption on what the subject is and why anyone should need it. In another part of the book Etter mentions the length of the instruction depends on the consumer. This document is intended for anyone who wants to create their own website and thus it is more detailed.
   

### Using a site generator to add themes
Jekyll is a site genarator that is built-in in GitHub Pages. We can use Jekyll to generate themes for your website.

1. To add themes to your resume, create a "_config.yml" file
2. Inside the "config.yml" file add the line "theme: jekyll-theme-slate"
  - "slate" is the theme name. To use other themes, we can replace it with other theme names such as "minimal", "cayman", "hacker", etc.

Andrew Etter in his book mentions to use site generators. These tools makes it easy to create websites. There are many site generators like, Spinx, Jekyll, Hugo, etc. but Jekyll is the most popular out of them. We  can also use themes in your static website as it a way to make your website stand out. Themes allow custiomization which can make your website more organized and user-friendly. Etter puts a lot of emphasis on this even suggesting to consult professionals in needed.


### Downloading and installing Jekyll
Depending on your device, you may need to download and install Jekyll for your device

1. Install the following:
   - Ruby version 2.5.0 or higher
   - RubyGems
   - GCC and Make
2. In terminal, type ``gem install jekyll bundler`` to install jekyll
3. Create a new Jekyll site, ``jekyll new myblog``
4. Move to that directory using, ``cd myblog``
5. Build the site, ``bundle exec jekyll serve``
6. Search ``https://localhost:4000``

Some devices might work without needing to do this step but it is always a good idea to include instructions that may be required.

Etter also breifly mentions the need to use inline styles to highlight text that are important. 
   

### Animated gif
An animated gif of the resume.

![cv-gif](https://i.makeagif.com/media/3-07-2024/QaYIpx.gif)



## More Resourses
1. [Markdown Tutorial](https://www.markdowntutorial.com/)
2. [Mardown Editor: Dillinger](https://dillinger.io)
3. [Guide to Markdown](https://www.markdownguide.org/getting-started/)
4. [Guide to GitHub Pages](https://docs.github.com/en/pages/quickstart)
5. [Guide to Jekyll](https://jekyllrb.com/docs/)
6. [Guide to using Jekyll in  GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
7. [Gif Maker](https://makeagif.com/)



## Authors and Acknowledgements
Thanks to Andrew Etter the Author of *Modern Technical Writing* which was a key component in creating this website and its documentation.

This README was written using the template provided by Billie Thompson [PurpleBooth](https://github.com/PurpleBooth)

Thanks to Souvik Ray and Jahidul Islam my Team Members who helped me by peer reviewing my files and pointing out errors and mistakes. 



## FAQs
Q. Why is Markdown better than a word processor?

A.  There are several reasons why markdown is better,
    - Markdown is very lightweight markup language with a very clean syntax
   - Markdown is more versatile. You can use it to create websites, notes, techinical documentations etc.
   - Markdown takes up very less memory to be created which is why it is also very easily portable.
   - It can be opened by any application no matter the operating system and created on any device.
   - If some modification is required the effort needed is very low.

   - Word processor such as Microsoft Word is a very good tool to write texts but it unsuitable for creating websites.
   - It is not very versatile as it is only available for Windows and macOs operating systems.
       

Q. Why is my resume not showing up?

A. There can be multiple situation where the resume might not show up. 
  - Error in repository name: the reporsitory name has to in the format username.github.io. If it is not in this format the      page will not generate.
  - If the correct branch from which the site is generated is not selected.
  - If the resume is in the wrong file: the resume has to be in the file labelled index.md

Q. Why use GitHub pages to host your website?

A. GitHUb Pages is availabe for free for anyone with a GitHub account. GitHub Pages can be used to host personal or professional website very easily. It is very customizable with site generators such as Jekyll and websites with custom domains can also be created using GitHub Pages. 


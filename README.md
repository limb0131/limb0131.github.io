# How to Host and Format a Resume
## Purpose
The purpose of this README is to provide you with the steps required to host and format your resume on Github Pages. Furthermore, we will analyze Andrew Etter's book "Modern Technical Writing" to incorporate its principles into our resume. 
## Prerequisites
The prerequisites to get started will include the following:
- A resume formatted in Markdown (See link under More Resources to learn more).
- Basic knowledge on how to use Github.
- A Markdown editor (Recommended).
- Andrew Etter's book "Modern Technical Writing" (Recommended. Link to book under More Resources).
## Instructions

This is a step-by-step guide on creating a properly formatted resume and hosting it on Github Pages.       

### Hosting your Resume on Github Pages

  1. Log in to your Github account and create a new repository with the name `[GithubUsername].github.io`. Make sure the field `[GithubUsername]` is changed to fit your accounts username.
     
     - Creating a new repository can be done by locating the "+" sign at the top right of the webpage.
       
  3. Now that you have the proper repository, you should now able to upload your resume to the repository by clicking on the "uploading an existing file" link.
      
     - Once you've located your resume, add the file along with a description for a commit message, which will help identify what was done when the latest changes were commited.
       
     - This is where the importance of version control can be identified, as we are given access to the history of all changes made in the repository. After you save a file, you could make as many changes as you wish without the worry about losing your original work. Since you have the version control history, you are able to retrieve older versions of your document whenever you feel the need to go back. 
       
  5. Now that your resume is in the repository, the last step is to rename your resume file from `[YourResume].md` to `index.md`.

     - Once you've changed your file name and saved the changes along with a commit message, you are done!
    
  6. Congratulations! Your resume should now be hosted on Github Pages.

     - To verify this is the case, nagivate to `[GithubUsername].github.io`. The link should nagivate you to your webpage where your resume is displayed.
    
     - If this is not the case and you are not able to see your resume, give it a couple minutes for the system to upload your files to the server, as it may just be an issue of upload times.
    
     - If your resume is still not displayed on your page after being refreshed a couple minutes later, look back at the instructions and make sure you have followed the steps correctly.
    
### Optional Steps:

  1. If you find that your webpage is looking a little plain, you have the option of adding a theme using one of the pre-made jekyll themes.

      - These themes may be found in a link found under More Resources.
      
  2. Once locating a theme that you are happy with, create a file named `_config.yml` in your repository.

      - A new file can be added to the repository by clicking the "+" beside the green button that reads "code", which can be located at the top of the repository view.
    
  3. Now that you have your new file, edit the file with the line `theme: jekyll-theme-[nameofyourtheme]`.

     - Make sure to change `[nameofyourtheme]` with your chosen theme. In this tutorial, the theme `slate` was used, resulting in `theme: jekyll-theme-slate`

  4. Finally, save the file with an appropriate commit message and you are done!. Just wait a few minutes for the theme to get applied and watch your webpage come to life!

### Final View of the Webpage:

  If you have followed along with this tutorial properly, you should end up with the following. If you have not applied any jekyll theme or have chosen a different one, your webpage may look slightly different from the provided output.

![demogif](https://github.com/limb0131/limb0131.github.io/assets/66758985/02b105f4-ebe8-4b2e-a255-1061d65bdba5)


## More Resources
Mardown Tutorial: https://www.markdownguide.org/

Github Tutorial: https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

Github Pages Tutorial: https://pages.github.com/

Andrew Etter's book: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS

Jekyll Themes: https://pages.github.com/themes/

## Authors and Acknowledgements

  First, I would like to start off by thanking my 3040 professor Prof. Wilcox for providing me with the necessary information required to learn more about modern technical writing. I would also like to thank my 3040 group members for helping review and revise my writing. Lastly, I would like to thank the developer of the jekyll theme "slate" for allowing the public to access and utilize his work.
  
## FAQs

Q: **"Why do I want to format a document with a static site generator?"**

   - Building your resume on a static site generator can help you keep your resume up to date. You may have come across time where you have multiple files with the same name, but with a number such as "(1)". Files such as PDFs saved to your computer does not override the existing one, instead creating a duplicate. Hosting your resume online will give you the power to have a single file synced with the latest information.

Q: **"Markdown is too hard. Do I have to use it?"**

   - When first interacting with a language such as Markdown, it may feel kind of daunting but don't let this discourage you. You will learn that it is not much different with what you may be used to doing, just with a few extra things that give you more control.

Q: **"Why is Markdown better than a word processor?"**

   - Although Word is great for a simple writing task, Markdown is better in the sense that it gives the user more control over the whole process. Think of Markdown as taking the training wheels off, leaving you with better control and freedom of your work once you've learned the basics. Furthermore, in addition to giving you more control over your work, it is simple to read and understand, making it a great tool to utilize.

Q **"Why is my resume not showing up?"**

   - This may be due to the server not yet fulling processing the file you have uploaded. Give it 5-10 minutes before refreshing the page. If it is still not showing up, make sure you have named the files and repository correctly.

How to host a resume on GitHub
===

Purpose
---
In this README file, you will find a guide on how to create and format an online resume using *GitHub*. The process involves using a few tools, including a markup language called *Markdown*, a text editor such as *Visual Studio*, and a static site generator called *Jekyll*. Additionally, this guide includes steps on how to host your online resume on *GitHub*, which is a Distributed Version Control System (DVCS). With these tools and steps, you will be able to create a professional-looking online resume that is easily accessible to potential employers.

Prerequisites
---
To create your resume, you should use a formatting language called *Markdown*. *Markdown* is easy to learn and widely used for documenting text. Andrew Etter, in his book, explains that *Markdown* has clean syntax and makes it convenient for others to contribute to your document. There are many text editors available for creating *Markdown* documents, but *Visual Studio* is a great option because it has a live preview feature that makes editing easier.

You will also need a *GitHub* account to host your static site. *GitHub* is a distributed version control system that allows you to store and manage your code and documents online. By using *GitHub*, you can share your work with others and collaborate with them in real-time.

Instructions
---
1. **Create a GitHub account.**
    1. Go to [Github](https://github.com/).
    2. Click on Sign up button if you do not have an account.
    3. Enter your email.
    4. Click on continue.
    5. Create a password.
    6. Click on continue.
    7. Enter your user name.
    8. Click on continue.
    9. Verify your account by solving a puzzle.
    10. Click on create account.
    11. Enter the verification code that is sent to your email.
    12. Click on continue and you will see your dashboard.
2. **Create a new repository on GitHub.**
    1. Click on the "*+*" sign to the left of the profile logo on the top right corner.![Respritory](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/NewRes.png)
    2. Click on new repository.
    3. Name the repository as your username.github.io.
        > :warning: Ensure that your username for username.github.io matches your GitHub username. Additionally, verify that you have created a repository with your GitHub username to ensure proper operation. Please confirm that both of these conditions are met to avoid any potential issues..![Username](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/username.png)
    4. Make your repository public by selecting the public option.![public](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Public.png)
    5. Scroll down to uncheck add a README file for now.
    6. Scroll down to choose a licence.
    7. Click on create repository.![Create Respotory](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/CreateRes.png)

3. **Add files to repository.**
    1. Click on add a file.![Add file](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/Upload%20file.png)
    2. Drop your markdown-formatted resume and a README, if you have one, on the drop box.
    3. Add a title in the commit box.
    4. Click on commit changes button.
> According to Andrew Etter's book Modern Technical Writing, using Markdown language has several benefits. Markdown allows for easy syncing with the latest version of your work, and it supports multiple version control, making it simple to update and format your resume. Markdown also facilitates contribution, and it is widely used by developers in technical writing.


4. **Create a static website using Jekyll theme.**
    1. Click on settings.![Settings](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/Settings.png)
    2. Go to pages.![pages](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/Pages.png)
    3. Click on source to set the branch to main.![main](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/Main.png)
    4. Click on save option.
    5. Click on choose a theme which will navigate to a page having a wide range of themes. 
    6. Choose your desired theme for your resume.
    7. Click on select theme. 
    8. Click on commit changes button.
    9. Go to your repository.
    10. Select the _config.yml file and *add title: Resume* to change the title.
    12. Create your static website in *About* Setting section. ![Setting](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/Settings.png)
    13. Type https://username.github.io/ (your user name) to see the static website in *Website* section.![link](https://github.com/Rafia0388/Rafia0388.github.io/blob/main/Images/Website.png)
    14. Click on *Save Changes*
> As per Andrew Etter's book, using Jekyll as a static site generator can help you create a static website. Jekyll can make your Markdown content on the website look visually appealing, resulting in a cleaner presentation of your content.Additionally, he mentioned that moving the entire website is effortless as it doesn't depend on any third-party application or database, making it easy to relocate.

**Your final resume should look like this website.**\
![gif](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmQ4YTNmYTc5MDZiNTM3Y2I1YjVlNzdlOTU0NjY4NWQxMDVlZmQyZSZjdD1n/EspUgeBW8NKVsS9kIT/giphy.gif)

More resources
---
* [Modern technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Markdown Tutorial](https://www.markdownguide.org/basic-syntax/)
* [Visual studio](https://code.visualstudio.com/docs/languages/markdown)
* [Minimal Jekyll Theme](https://pages-themes.github.io/minimal/)

Authors and Acknowledgments
---
* Etter, Andrew. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), 2016.


FAQs
---
1. Why is Markdown better than a word processor?
> Markdown is a plain text format that is simpler to learn and use than word processing software. It has simple and easy-to-remember syntax. Markdown generates code that is cleaner and easier to read than code generated by a word processor. It is more adaptable and can be converted to various file formats without losing formatting. Markdown is more efficient because it can be written quickly and easily with any text editor and does not require specialised software. 
2. Why is my resume not showing up?
> Your resume may not appear on Github pages for a variety of reasons, including an incorrect file name, repository location, branch, or file path.Check that these elements are correct and meet the requirements of Github pages for displaying your resume.You can ensure that your resume appears on Github pages by identifying and addressing these issues.

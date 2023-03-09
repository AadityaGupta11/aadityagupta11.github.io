HOSTING A RESUME THROUGH MARKDOWN, GITHUB PAGES AND JEKYLL

PURPOSE:

Describe the practical steps of how to host and format a resume using the software stack Markdown, GitHub Pages and Jekyll. Also, relate the practical steps to the general principles of current Technical Writing, as explained in Andrew Etter's book Modern Technical Writing.

Prerequisites:

A Markdown resume

Github Pages

Jekyll

A web browser to support Github

A Markdown Editor

Instructions:

Instructions to host a resume on Github using Jekyll and a Markdown editor.

For Markdown editor:

`	`Headers:

`		`Markdown #Heading Level 1

`		`Heading Level 1



`		`Markdown ##Heading Level 2

`		`Heading Level 2



`		`Markdown ###Heading Level 3

`		`Heading Level 3



`	`Numbered Lists:

`		`Types of numbered lists are:

`		`#.one

`		`#.two

`		`#.three



`		`i.four

`		`ii.five

`		`iii.six



`		`(A)seven

`		`(B)eight



`		`1)nine

`			`a)ten

`			`b)eleven

`		`2)twelve

`			`a)thirteen

`			`b)fourteen

Step 1: Creating a Github Account:

Visit https://github.com

Click on Sign up.

Enter your email address. Click Continue.

Create a strong worded password and click Continue. Enter a username for your Github account and click Continue.

Then, for more information about products updates and to receive important annoucements, press "y" for yes or "n" for no. Click Continue.

To verify your account, solve the puzzle. Press Start Puzzle and then follow the prompts.

After you are done, Click on Create Account.

Next, enter the code from your email to the following dialog box to verify your email. It will automatically take you to the next page.

Now, Welcome to Github will pop up. It will ask some questions regarding yourself and after that, it will ask questions about what features you are interested in Github. Click Continue.

Github will show you the bundles available. You can use for free by pressing Continue for free, or pay if you want. Now a personalized page opens up.

Step 2: Create a new Repository:

Click on create repository(the green icon) on the left hand side of the screen or click on the "+" sign on the top right hand side of the screen and in the drop down menu click new repository.

A create new repository screen appears. Type in the new repository name. Add some description about your repository.

Choose if you want your repository to be Public or Private. Click on "Add a README file" under initialize this repository with. Then, click Create Repository.

Step 3: Adding resume to the repository:

Go the main page of your repository.

Click on Add files, in the dropdown menu, Select Upload files.

Next, you can drag and drop any file you want, or select choose files to choose from a specific location.

You can also add description about the changes in your file on the repository. The commit changes section below allows to add the changes either to the main branch or to a new branch.

After you are done, click on Commit Changes.

Step 4: Rename the resume file:

In your repository, browse to the branch where your resume is in. Click one the file resume.

Then, click on the pen shaped icon on the right hand side of the screen to edit the file or renaming the resume file.

When you are done, you will a commit changes section below, Add a description about the changes to the file pin the repository and to select a different branch if you want. When you're done, click Commit Changes.

Step 5: Set up Github Pages:

Go to Settings in your repository.

On the left hand side, select Pages.

Select Deploy from a branch under Source and select the main branch.

Click on Save.

Step 6: Creating a file for Jekyll:

Click on Add file, in the dropdown menu, Select Create new file.

An empty filename and file editor box appears. For the file name, type in \_config.yml and in the editor box, write the following;

remote\_theme: pages-themes/slate@v0.2.0 # this line adds the slate theme of Jekyll. You can replace "slate@v0.2.0" with your preferred theme.

plugins:

- jekyll-remote-theme # add this line to the plugins list if you already have one

title: "RESUME OF [Your Name]"

Click on Commit Changes when done.

Find animated gif from internet


More Resources:

Markdown Tutorial : https://www.markdowntutorial.com

A link to Etter's book :

Jekyll Template : https://jekyllrb.com

Github link to my resume :

Authors and Acknowledgements:

Andrew Etter

FAQs:

Why is Markdown better than a word processor?

Markdown is simple and fast. It is a light weight text language with simple writing and editing. Markdown uses fewer formatting options and provides more accessibility to the user. Even with just the basic knowledge, anyone can create a perfect looking document.

Markdown is less distractive. It has less distractions with almost no toolbar present, and the mouse clicks are also reduced so the user can keep their hands on the keyboard and can have more productive and structured content writing. It provides seamless experience with more control and less autocorrect.

Why is my resume not showing up?

Usually when are files are dragged onto the the GitHub page, they are instantly visible. However, if the user is working with a certain set of settings then they will need to change it by going to the repository setting. Or worst case scenario, that the Github servers are down. Please do wait for aa few minutes and refresh the page and it will appear.

Can you add multiple files at once including your resume on the same repository?

Yes, multiple files can be added to the same repository including your resume. The user can add a specific document or a specific file and they can also add a whole folder from their system. Just follow the instruction given above and the file/folder will be added to the same repository.

How to install Jekyll to the Github Pages?

To install and use Jekyll on the Github Pages:

Firstly, install Jekyll on your personal system(device).

Secondly, after installing go to https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll to add Jekyll onto your Github pages.

Thirdly, for more information, visit https://pages.github.com.
































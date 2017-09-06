# Lab - Getting Started with GitHub and Cloud9

This lab assumes you have already created your GitHub and Cloud9 accounts; if not, look at (https://github.com/IT202/lab-creating-accounts)  


We're going to minimize problems by following a simple workflow.

1. Create an empty repository on GitHub.
2. Create a new Cloud9 workspace that is a clone of that GitHub repository.
3. Edit and save files on Cloud9.
4. Update your Cloud9 repository and push to GitHub.


## Step 1 - Create a GitHub repository.

Navigate to GitHub, log on, and create a new repository named "lab-test", selecting the "intialize with a Read Me file" option.

Find and copy the *clone* URL.

## Step 2 - Create a Cloud9 workspace.

Navigate to Cloud9, log on, and create a new workspace named "lab-test".

On the new workspace page, paste the GitHub URL, use the HTML5 template and create a new workspace.

## Step 3 - Create a new file in your Cloud9 workspace.

Open your workspace, and from the menu, select File > New From Template > HTML file.

Add a paragraph element with some text to the file, and save;  name it test1.html .

From the menu, select Preview > Live Preview File to display it.

Click the pop-out icon to see your page in a separate tab.

## Step 4 - Update your local Git and push to GitHub

In the C9 terminal window, run `git status` and note the message;  it's indicating that the file system has changes not reflected in the repository.

Run `git add *`; this will add all updated files to the repository.

Run `git status` again;  it's now indicating that those changes are not part of the most current project version.

Run `git commit -m "add new file"`

Run `git status` again.

Now you need to update your GitHub repository; run `git push origin master` and enter your username and pw as needed.

Open and refresh your GitHub repository page to see the changes.


# Blitz
## What is it?
This extension puts all pull requests across all repositories into a queue. This allows users to review open pull requests and click the link to go to work the pull request.

## Now with a Widget
Now, you have a widget that will show all active pull requests in your project across all repositories. Here's how it looks:
![Widget Showing Active Pull Requests](https://sierpinski.gallery.vsassets.io/_apis/public/gallery/publisher/sierpinski/extension/blitz-allpulls-extension/0.9.3/assetbyname/Microsoft.VisualStudio.Services.Screenshots.3 "Active Pull Requests Widget")

## Details
This is for VSTS (VSO, TFS 2015). This extension shows all of the open pull requests in a project. The approver can then follow a link to work the pull request.
Go here:
![Screenshot of Finding The Extension](https://sierpinski.gallery.vsassets.io/_apis/public/gallery/publisher/sierpinski/extension/blitz-allpulls-extension/0.9.3/assetbyname/Microsoft.VisualStudio.Services.Screenshots.2 "Finding the Extension")

## Screenshot
Here is an example list of pull requests:

![Screenshot of Active Pull Requests](https://sierpinski.gallery.vsassets.io/_apis/public/gallery/publisher/sierpinski/extension/blitz-allpulls-extension/0.9.3/assetbyname/Microsoft.VisualStudio.Services.Screenshots.1 "Screenshot/Active Pull Requests")

## Features In Latest Update(s)
## Hotfix to remove XSS vulnerability. 0.9.4
A potential XSS vulnerabilty is removed.
New features:
* Streamlined code; fixed bug in links on-premises.
* Widget!!! Check out the widget screenshot above. You can add it to your dashboard!
* Filter to only pull requests to which you have been assigned as a reviewer.
* Hover over Reviewer for more information on their vote.
* Rows now styled to show whether the pull request merged successfully with master.
* Repository name added.

## Why did I make it?
Our state's mail server went down and pull requests fell through the cracks. We also had some pull requests which dropped off the radar before they were completed. I just wanted a solution to see all of the pull requests across hundreds of repo.'s. So, I made one!

## Source Code and Issue Reporting
I've added the source to [my GitHub repository](https://github.com/sierpinski/Blitz). Please open issues with the extension there so I can track them more easily.

## Feature Ideas
Dive into code policies and more detailed statuses for each pull request.

## On-premises Issue - RESOLVED!
All features available on TFS 2015.3 or later.
I fixed an on-premises issue that prevented pull request links on the pull request table from opening properly.

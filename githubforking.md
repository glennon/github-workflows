<strong>When to Fork</strong>  

There are two common use cases for forking a GitHub repository, to:
* Make personalizations and customizations
* Contribute code to others' projects

**Customizing and personalizing a repository**  
Many repos possess functionality that are suited for individual personalization and customization. For example, a repo might possess a webpage template, and your personalizations would be inappropriate to push back to the original source. When using other people's code, make sure its license is compatible with your intended use.  

The simplest workflow for this case is--from the repo's GitHub page--to press the Fork button in the upper right of the user interface. GitHub will place a copy of the repository into your account. When you complete edits or create files in this forked (copy) repository, GitHub's *Comparing Changes* offers a pulldown menu of where your changes currently reside (*head fork*) and where the Pull Request will be written (*base fork*). Be cautious that you do not accidentally save to the original project; double check that both the *head fork* and *base fork* should be pointing to branches in your account. If it points to the original source, use the pull down menu to change it.  

It is possible to forget the original *base fork* location and reassign it permanently to your account, but using GitHub's import page. Via http://import.github.com, a repository can be copied to your GitHub account and the *base fork* will be set by default to your account; in essence, GitHub ignores and forgets about the original repository source. Such imports usually are intended for projects originating from other verson control systems. However, it is also useful when forking a repo for personalizations that will not be contributed back to the original project.

**Contributing to others' repositories**  
GitHub has automated much of this workflow. On GitHub.com, if you begin editing a file within a repository which you do not have write permission, the system will create a fork of the repository under your account. At the top of the editing page, you are likely to see the message: <blockquote>You’re editing a file in a project you don’t have write access to. We’ve created a fork of this project for you to commit your proposed changes to. Submitting a change to this file will write it to a new branch in your fork, so you can send a pull request.</blockquote>

If you save your edit (propose a change), the fork will be created and a typical pull request (a *Comparing changes* page) from your fork to the original fork is initiated. GitHub calls the original repo the <i>base fork</i> and the modified version in your account, the <i>head fork</i>. When the pull request starts, notice that the path to the head fork includes your account name.

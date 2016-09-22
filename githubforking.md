<strong>When to Fork</strong>  

There are two common use cases for forking a GitHub repository:
* to customize it
* to contribute when you do not have write permissions

**customizing a repository**  
Many repos possess functionality that are suited for individual customization. For example, you might want to use a repo with a webpage template, but your personalization would be inappropriate to push back to the original source. Of course, make sure the license on any repo has a license compatible with your intended use.  

The simplest workflow for this case is, at the repo's GitHub page, press the Fork button in the upper right of the user interface. GitHub will create a copy of the repository into your account. When you edit or create files in this forked repository, be cautious that you do not accidentally create a Pull Request to the original project. In the *Comparing Changes* page, you will want to be sure that the base fork points to your account and repository. If it points to the original source, use the pull down menu to change it.  

When a project is cloned or forked in GitHub, the default settings are for your changes to be resubmitted back to the original project repo (not just your version). However, there may be cases when you do not want to submit your changes back to the original repo. For instance, in the geospatial industry, some repositories are offered as templates for creating your own map. Your changes are not improvements to the original project, but rather personal customizations. If that is the case, GitHub has a special import function. Using http://import.github.com, a repository will be copied to your GitHub account, but your changes will not automatically be sent back to the original project. Such an import is generally intended for projects originating from other verson control systems. Using Import, the <i>base fork</i> will default to your account's version of the repo.


**contributing to to someone else's repository**  
GitHub has automated much of this workflow. On GitHub.com, if you begin editing a file within a repository which you do not have write permission, the system will create a fork of the repository under your account. At the top of the editing page, you are likely to see the message: <blockquote>You’re editing a file in a project you don’t have write access to. We’ve created a fork of this project for you to commit your proposed changes to. Submitting a change to this file will write it to a new branch in your fork, so you can send a pull request.</blockquote>

If you save your edit (propose a change), the fork will be created and a typical pull request (a *Comparing changes* page) from your fork to the original fork is initiated. GitHub calls the original repo the <i>base fork</i> and the modified version in your account, the <i>head fork</i>. When the pull request starts, notice that the path to the head fork includes your account name.

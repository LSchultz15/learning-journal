# Review of git, the differences with GitHub, and Cloud Connectivity for  Repositories
## (102 Read 03: Discussion)

**What is git?**
    git is a version control system, meaning that you can easily save changes to a repository, view and share detailed information on changes with others, and even directly collaborate with other developers. This is slightly different that saving multiple versions of a file however, as you may have done in the past with files on your computer. Rather, git allows you to "commit" changes to the repository without losing the ability to review past changes - like a snapshot on a timeline rather than a duplicate.
    
Thanks to online cloud tools such as GitHub (which is distinctly different than git), it is possible to make changes to your repository in a Graphical User Interface such as VS Code and subsequently "push" those changes to your repository in the cloud on GitHub through a Command Line Interface such as the Terminal.

    `Terminal git Control Code Examples:

      git clone= Create a clone of a repository existing on the cloud for your local machine

      git remote -v= Lists the url that your Command Line Interface is using to pull information from and send information to.

      git status= Analyzes the current status of the repository on your local machine against the repository on the cloud for changes.

      git commit= This is the "save" button for changes to your repository.

      git commit -m ""= When information is "added" or "updated" between the quotations, a message can be added along with your "save" to assist in the tracking of changes, notify other developers of specific items, etc.

      git push= Pushes any locally committed changes to your repository to the cloud version.
  
**How is GitHub different than git?**
  Though GitHub utilizes git, they are significantly different. git is a version control system that allows you to track, view, and edit changes to your repository along with a save system that acts as snapshots on a timeline rather than the duplication of files. GitHub is an online cloud-based user interface and hosting service for repositories, and uses git for those repositories.

**What is a Repository?**
  A Repository is a collection of files used in creating code. In fact, what you're reading right now is content in a file that exists within a repository. Think of it like a large master folder for a project.

[Return to README](/README.md)
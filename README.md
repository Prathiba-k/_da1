# _da1

           PROCESS OF CITHUB WORKING METHODALOGY:

What is GitHub?

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

Step 1. Create a Repository:
A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs.. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.
To create a new repository:
1.In the upper right corner, next to your avatar or identicon,click  and then select New repository.
2.Name your repository
3.Write a short description.
4.Select Initialize this repository with a README.


Step 2. Create a Branch:
Branching is the way to work on different versions of a repository at one time.By default your repository has one branch named main  which is considered to be the definitive branch.
When you create a branch off the main branch, you’re making a copy, or snapshot, of main as it was at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.
To create a new branch:
1.Go to your new repository
2.Click the drop down at the top of the file list that says branch: main.
3.Type a branch name, readme-edits into the new branch text box.
4.Select the blue Create branch box or hit “Enter” on your keyboard.

Step 3. Make and commit changes
On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.
Make and commit changes:
1.Click the README.md  file.
2.Click the  pencil icon in the upper right corner of the file view to edit..
3.In the editor, write a bit about yourself.
 4.Write a commit message that describes your changes.
5.Click Commit changes button



Step 4. Open a Pull Request:

Pull Requests are the heart of collaboration on GitHub. When you open a pull
request, you’re proposing your changes and requesting that someone review and
pull in your contribution and merge them into their branch. Pull requests show diffs
Or differences,of the content from both branches.
ou can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub flow before working on larger projects.
Steps:
1.Click the  Pull Request tab, then from the Pull Request page, click the green New pull request button.
2.Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit.
3.When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button

Step 5. Merge your Pull Request:
In this final step, it’s time to bring your changes together – merging your readme-edits, branch into the main branch.
1.Click the green Merge pull request button to merge the changes into main.
2.Click Confirm merge.
3.Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.


Ways to access github:

    Go to github website look in the upper right comer and click the + sign and then click “new repository “.Name the repository and add a quick description .Click  initialize this repository with a README .if you want include the README file.

Pros of GitHub:
* It’s free and it is open source:
 github is completely free and you can use it without paying and since it is an open source you can download the source code and can make changes as per the requirements.
* It is fast:
Since most of the operations are preferred locally, it allows huge benefit in terms of speed.
* It provides good backup:
Here chance of losing data is very low as it provides the multiple copies of it.
* Multiple developers can work:
Github allows multiple developers to work on a single project at a time. It helps all the team members to work together on a single project at at a time from different locations.

Cons of github:
* Potential Drawback: Security
GitHub does offer private repositories, but this isn’t necessarily perfect for many. For high value intellectual property, you’re putting all of this in the hands of GitHub as well as anyone who has a login, which like many sites has had security breaches before and is targeted constantly. It is often better than nothing, but it’s not perfect.
* Potential Drawback: Pricing
Some of GitHub features, as well as features on other online repositories, are locked behind a SaaS paywall. If you have a large team, this can add up fast. Those who already have a dedicated IT team and their own internal servers are often better off using their own internal git for cost reasons, but for most the cost isn’t outrageous.



Version controls Applications:


1)Revision Control system:
          (RCS), developed by Thien-Thi Nguyen works on the local repository model and supports Unix-like platforms. RCS is a very old tool and was first released in 1982. It is an early version of VCS(Version Control System).

Features:

Was originally intended for programs, but, is also helpful for text documents or config files that often get revised.
RCS can be considered as a set of Unix Commands that permits various users to build and maintain program code or documents.
Allows revision of documents, committing changes and merging docs together.
Store revisions in a tree structure.

Pros:

Simple architecture
Easy to work with
It has local repository model, so the saving of revisions is independent of the central repository.
 
 Cons;

Less security, version history is editable.
At a time, only one user can work on the same file.
Open Source: Yes

Cost: Free

2)Virtual sourcesafe:

   VSS by Microsoft is a Shared folder repository model based revision control tool. It supports Windows OS only.

It is intended for small software development projects.

Features:

Creates a virtual library of computer files.
Capable of handling any file type in its database.
Pros:

Fairly easy to use interface.
It lets a single user system to be assembled with fewer configurations when compared to any other SCM systems.
Easy backup process.
Cons:

Lacks many important features of a multi-user environment.
Database corruption is one of the serious problems noted with this tool.

Cost: Paid. 
 
 3)darcs:
    (Darcs Advanced Revision Control System), developed by The Darcs team is a distributed version control tool that follows merge concurrency model. This tool is written in Haskell and supports Unix, Linux, BSD, ApplemacOS, MS Windows platforms.

Features:

Capable of selecting which changes to accept from other repositories.
Communicates with local and remote repositories through SSH, HTTP, email or unusually interactive interface.
Works on the concept of linearly ordered patches.
Pros:

Has fewer and more interactive commands when compared to other tools like git and SVN.
Offers send system for direct mailing.
Cons:

Performance issues related to merging operations.
Installation takes a long time.
Open Source: Yes

Cost: This is a free tool.


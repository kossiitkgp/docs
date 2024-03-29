# Git & Github Workshop

## Aim of the Workshop

The workshop should cover and explain the following

- Why Version Control Systems are needed?
- Usage of basic Git commands to track their projects - Staging and Committing
- Be able to push and pull code from GitHub
- Be able to send a PR to an Open Source Repository

## Timeline  
The Workshop should be held around the time when Gymkhana societies have their introductory seminar so that we also show our presence during the same time but with a workshop.
Gymkhana societies have their introductory seminars in mid-August, so it's best to conduct the Workshop by the end of August.
## Before the workshop

Share an instructions file like [this installation guide](https://github.com/kossiitkgp/events/blob/main/2023/Autumn/Git-github/installation.md), along with the poster of the workshop. The instructions should contain

- How to install Git for Windows, Linux, and Mac separately
- For Windows users, make that they install `git bash` and configure it
- How to verify that git is installed
- Instructions on how to create a Github Account

In the post mention the fact that we will be available for installation issues before 15 minutes of the workshop. Help with the installation issues before the workshop begins.

## Connecting Github Account
While SSH authentication is a secure and efficient way to interact with GitHub, it may not work on the campus network.  
Alternative :
- Use Personal Access Tokens.
- Use Browser Login Method.

## Flow of the workshop

0. **How will the workshop proceed**

   Explain that Git and GitHub are important parts of Software Development. Tell them how the workshop will proceed like when should audience ask queries. Tell the audience that doing hands-on by themselves along with the workshop will help them learn better. Encourage them to ask questions, as some of the Git concepts are non-intuitive.

1. **Terminal Commands**

   It might be a good idea to introduce basic Linux Commands, as they will be used throughout the workshop. You don't have to cover this topic in detail. Just important commands like - `ls`, `cat`, `echo` , `cd`, `mkdir`, `pwd` , `rm` would suffice. Windows users can be asked to try these commands on Git Bash. 

2. **Why do we need something like Git**

   Before teaching anything, it is important that the audience understand why they are learning it. Start with an example, with which they can connect. Note that most of the audience might not have collaborated on a software. You can give an example of a folder, containing so many files, which are regularly updated. Tell them that tools called "Version Control Systems" are used to track projects. Tell them the importance of maintaining History and backups. Then you can tell that how such tools are useful in Software development and conclude that Git is used to track Software projects.

3. **Mental Model of Git**:

   Directly jumping to the terminal would confuse the audience. It might be frustrating for the audience to type commands that they don't understand. Hence, first explain how Git tracks your project. Tell that Git stores snapshots of the project and each snapshot is referred as a commit. You can show a `git log` of a good project, to convey the idea of how snapshots are taken at every feature. 

   Explain the idea of staging area very carefully and clearly. Tell them that before storing snapshots, it is important to add them to a staging area. Show them a picture depicting the workflow - 1. git add 2. git commit.

   <u>Note</u>: Though it might be tempting to introduce the concepts of Decentralized VCS and Centralized VCS, Merkle Tree. Please refrain from jumping to complex concepts. We have only 3 hours. It is important that we convey them knowledge of practical usage. One can use Git comfortably without knowing Merkle Trees. But making audience comfortable with Git requires some time and effort. So, it's worth investing time in making the basics strong. However, you can share the links/resources to such concepts at the end of the workshop for the curious audience.

4. **A demo**

   A small demo of how a git repository is initialised. Creating files and adding them to staging area. Commit the changes. While you are typing the commands, do explain the audience what these commands do. For example, while typing `git add FILE` , tell them that now this will add `FILE` to the staging area. You can use `git status` after each command to show the status of changes - changes have been staged, changes have been committed. 

   Though any demo works, it is a good idea to demonstrate something that's closer to daily life examples. For demo purpose, you can create a project as a "Facebook clone". You don't have to write any real code. You can simply create a text file and something to demonstrate that some X feature has been added, and commit it. The audience will indirectly absorb the idea the commits are made after every feature is added or after every bug is fixed.

5. **Stop and Revise**

   It is a good time to stop and revise the concepts. Staging area is a non-intuitive concept. Try using analogies to make the idea clear(For analogies [refer answer by Spoike](https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git)). Ask the audience if they have any doubts. In an offline session, TAs can individually clear people's queries. 

6. **Reverting using Git**

   This is better done using a demo. Show them the following

   - How to undo changes made after a commit using `git checkout
   - How to remove changes from the staging area
   - How to go back commits using `git reset --hard`

   (This can be done using a story. For example, an evil cat makes changes in your projects and you use git commands to revert those changes)

7. **Branching**

   Branching is another non-intuitive concept. You can start with a problem of how difficult it is to have multiple copies of a project with multiple people working on it. The problem should be posed in such a way that its ultimate solution has to be Git Branching. This will help them better understand why branches are important. You can show the commit trees of different branches and how they diverge. Also, show how the tree merges after git merge.

   Tools that can be used - [https://git-school.github.io/visualizing-git/](https://git-school.github.io/visualizing-git/)

8. **Branching demo**

   You can use the "Facebook clone" project for the demo. Make a branch for a new feature. Make some commits in the new branch and show the commits. Jump to the `master` branch and show that the newly made commits are absent(To convey the idea that different branches have different commits). Merge the newly created branch and show how commits have appeared. 

   Make sure to speak while you are typing the commands, explaining what the commands do. For example, tell them that you are creating a new branch while typing `git branch BRANCH` and tell them that you are hoping on to the newly created branch while typing `git checkout BRANCH`

   Again it is a good point to stop and summarise branching. Pause for a short period of time. Let the audience ask their queries. 

9. **Introduce Github**

   Now once the audience is comfortable with the basics of Git. It is the right time to introduce Github. Tell them, how Github is important for software development. Give an analogy of people writing a shared Google doc, and explain collaborative software development better.

10. **Push and Pull**

    This is best explained via demo. First, show them how to create SSH keys and how to add the generated keys to Github. Show them how to make a new repository on GitHub. 

    Show them how to push the local project to the Github repo using `git push git@github.com:USERNAME/REPONAME.git master`. Make a README on repo on GitHub. Show them how the changes on the Github repo can be obtained locally via `git pull git@github.com:USERNAME/REPONAME.git master`.

    Tell them typing the URL is a pain every time, and use this as an opportunity to introduce the concept of remote variables. Add a remote by name `origin`  using `git remote add origin` and show how `git push origin master` does the same job.


11. **Sending a Pull Request**

    This is also best explained via a demo. Use the [sandbox](https://github.com/kossiitkgp/sandbox) repo. Make a small issue like a  "typo in `printf` function" which anyone can solve. Follow up the whole process from checking the issues, comment on issue you want to work on, Forking the repo, Cloning it, Making a new branch, Push it, Sending a Pull Request with a proper description. 

    While demonstrating each and every step explain clearly, why you are doing this. For example, tell them that you are forking the repo to have your own copy of the codebase. Similarly, make your explanation in such a way that steps have a logical sequence.

    After the demo, show them pictorially all the steps from Forking to Sending a PR. Ask the audience to send a PR. Tell them that sending the PR is the most important takeaway of the workshop. TAs in the workshop can provide individual assistance. If needed, you can show the demo again.

    Finally, merge a PR that contains a well-written description to complete the process. 

12. **Conclusion**

    - Tell them to contribute to beginner-friendly issues at metakgp or KOSS repositories on GitHub. Share the Github Links of both the Github Organizations. Pointing them to some beginner-friendly issues would be great.
    - Tell them about the Github Student pack and its benefits like Domains, Free Servers, and so on.
    - Tell them about Github Pages, and tell them how easily a beautiful blog can be set up within minutes.
    - Inform them about Hacktoberfest, GsoC & KWoC.
    - Tell them about starring a repo and the usefulness of starred repos.
    - Tell them about the "watch" feature of a repo, and show them how it can be used to track a project.
    - Ask them to `star` and `watch` the [events](https://github.com/kossiitkgp/events) repo, as important links like slides, and resources will be put here

    If any swags are available distribute them to the audience.

## After the workshop

Upload the following in the [events](https://github.com/kossiitkgp/events) repo:
- Recording of the workshop, if it's recorded
- Link to the slides
- Link to extra resources, from which they can revise or learn more advanced stuff. Something like [this](https://github.com/kossiitkgp/events/tree/main/2023/Autumn/Git-github/resources)

Share the above via a Facebook post along with a thanks to the audience.

## PLEASE DO NOT

- Introduce an idea or feature directly without explaining why it is needed. Just starting with "Branching is an important feature and to create a new branch, we use `git branch` command" is a bad way to introduce branching. Make sure you firmly establish in the audience's mind why they are learning. If you can't explain why in the beginning make a promise that it will be explained later and keep your promise. Otherwise, our workshops will be no different than most of the boring academic lectures.
- Skip hands-on sessions. Hands-on sessions are the main reason we conduct workshops, else the audience would have simply watched a tutorial video. Repeat demos if required. Provide individual assistance. Make sure the audience gets their hands dirty.
- Skip questions. Git contains many non-intuitive ideas. The audience may be confused while you are explaining the concepts. Re-explain things in a different way if necessary. Encourage the audience to speak out if they are confused. Tell them that Git is non-intuitive and it's okay to ask small doubts.

## KOSS Intro
Include 4-5 slides introducing KOSS, focusing on:
- when we do selections.
- why we do it at that time.
- what we expect from them.
- what they need to do/learn to get selected.

This introduction can be inserted in the middle of the workshop when the maximum audience is present.

## Miscellaneous
- We can also consider conducting an Advanced Git workshop, where concepts like `rebase`, `stash`, and `bisect` are taught. The duration of this workshop can be shorter than the duration of a regular workshop(3 hours). If such a thing is being planned, make sure to give some git exercises in the gap between git basic workshop and git advanced workshop, so that they are in touch with git concepts.
- `switch` is the new preferred way to switch branches. This might be included in the upcoming workshops. Refer [this](https://www.banterly.net/2021/07/31/new-in-git-switch-and-restore/).

## Feedback Form
Include an _anonymous_ form at the end of the slides and ask the audience to share their experience and suggestions.
Some questions to include in the feedback form can be (Including all the questions below is not necessary):  
- How well can you now explain Git-Github to someone totally new in this field?  (1-5)
- Can you revert a commit with errors now? (Yes / No)
- I don't want the changes made by you recently, which are not yet committed. Can you quickly roll them back? (Yes / No)
- How well did you grasp the concept of Git branching? (1-5)
- Are you confident enough to push that important file into the GitHub repository? Or try pulling the doc? (Yes / No)
- How well did you understand the flow of making a Pull Request? (1-5)
- How helpful were the workshop materials, such as slides and handouts, in your learning process? (1-5)
- Do you feel more confident in collaborating with others on GitHub after attending this workshop? (Yes / No) 
- Were there any specific topics or concepts related to Git and GitHub that you expected to be covered in the workshop but were not? (descriptive)
- Did you encounter any challenges or areas of confusion during the workshop? If so, please describe them. (descriptive)
- How did you find the pace of the workshop? (too slow, perfect, too fast)
- How likely are you to apply the knowledge and skills gained from this workshop in your future projects or work? (1-5)
- What more could we have done to improve your learning experience? (descriptive)
- How relevant and useful did you find the workshop? (1-5)
- Any other suggestions? (descriptive)

## Useful Resources
- [Git-School](https://git-school.github.io/visualizing-git/): Visualizating git.This can be used while the workshop
- [Git Parable](https://tom.preston-werner.com/2009/05/19/the-git-parable.html): Understanding Git concepts from ground up. It will be useful if speakers of the workshop go through this once. This can also be shared with the audience
- [Git Immersion](https://gitimmersion.com/index.html): A guided tour walks through the fundamentals of Git. This can be shared with the audience.
- [Git-The Simple Guide](https://rogerdudler.github.io/git-guide/): A handy cheat sheet. This can be shared with the audience. 

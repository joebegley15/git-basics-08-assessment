![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Challenge

Write your answers inside this file, where it's indicated by the comments.

1. We just forked a repo on GitHub.com and want to start working on it locally. What command do we use to do that?

Copy the link for the clone and enter the following code:
git clone yourclonedgit@somewhereongithub

2. OK, we just wrote some code. What command could we use to see a list of all the changes that have been made since the last commit?

We could use git status

3. Oops - it looks like there was a change that we forgot to include in our last commit. How can we revise that commit and fix things?

We could go back and say git commit --ammend

4. It looks like there was a change on the original repo that we forked from. How could we grab those changes and incorporate them into our local repo?

git fetch upstream

5. Suppose that we wanted to look at the third-to-last commit on `master`; what command(s) would we write to do that?

git checkout head~2

6. OK, we've done all the work we want to do locally. Let's update our fork so that we can make a pull request. What command would we use to update our fork?

You must create a branch and then add commits to the branch. You should push the code to the master. After that you go to Github.com and request a pull.
<hr>

You're done! Refer back to README.md.

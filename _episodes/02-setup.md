---
title: Setting Up Git
teaching: 5
exercises: 0
questions:
- "How do I get set up to use Git?"
objectives:
- "Configure `git` the first time it is used on a computer."
- "Understand the difference between Git and GitHub."
keypoints:
-   "GitHub Desktop is an easier way to start using version control on your local computer."
---

When we use GitHub Desktop on a new computer for the first time,
we need to configure a few things.

You'll see a welcome screen when you open GitHub Desktop.  Click 
"Sign in to GitHub.com" enter your GitHub username and password.  

![welcome](../fig/GitDesktop1.PNG)

You do not need a 
GitHub account to use GitHub Desktop (It's an open source program and
works even if you don't have a GitHub account - you could click on 
"Skip this step" on the welcome screen).  However, because we're 
going to be syncing repositories with GitHub later on in this lesson 
it makes sense to sign in now.

Next, we'll set our name and email address for Git.  A requirement of 
the Git version control system is that you set a name and email address.
These will be included with the history of changes made to a repository.

> ##
> > ## CLI Steps
> > When we use Git on a new computer for the first time,
> > we need to configure a few things. Below are a few examples
> > of configurations we will set as we get started with Git:
> > 
> > *   our name and email address,
> > *   what our preferred text editor is,
> > *   and that we want to use these settings globally (i.e. for every project).
> > 
> > On a command line, Git commands are written as `git verb options`,
> > where `verb` is what we actually want to do and `options` is additional optional information which may be needed for the `verb`. So here is how
> > Dracula sets up his new laptop:
> > 
> > ~~~
> > $ git config --global user.name "Vlad Dracula"
> > $ git config --global user.email "vlad@tran.sylvan.ia"
> > ~~~
> > {: .language-bash}
> > 
> > Please use your own name and email address instead of Dracula's. This user name and email will be associated with your subsequent Git activity,
> > which means that any changes pushed to
> > [GitHub](https://github.com/) or
> > another Git host server
> > in a later lesson will include this information. 
> {: .solution}
{: .challenge}

![welcome](../fig/GitDesktop3.PNG)

While this name and email doesn't need to be the same as the one in your
GitHub account, it's easier if they match.  Note that the default email from
GitHub is @users.noreply.github.com - this is a private address that is connected
to your GitHub account.  It doesn't accept email and ensures privacy. 

The weird robot image on the bottom left hand side is made up and shows how a commit
history will look.  This might get removed in a future release.

These configuration changes don't have to be added next time you start GitHub Desktop, but
can be modified under Preferences/Accounts and Preferences/Git.

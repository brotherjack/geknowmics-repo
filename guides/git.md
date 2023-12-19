# Introduction to Version Control Systems
In the very old days people writing software would send each other text files containing code (if they collaborated with other people at all). This usually worked well enough with maybe 2 or 3 people, but it often resulted in problems. The more people, the more copies of the same file would be circulating and the more chances that something would get lost or some change would break something, and then which version of the file would you use? Who has that old file, you know, the one Carol sent me Monday of last week.

This is the point of version control software. VCS, whether centralized or decentralized, provides a means of tracking and managing changes.

**How much do I need to know this?**

If you're interested in biotechnology or bio-informatics, you will need to learn how to work with VCS. Even if you are not, a passing familiarity with VCS could prove useful (for instance, this project is being hosted on a website designed around VCS).

Otherwise, you can safely ignore this for now.

**What should I learn in the short term?**

**GOOD NEWS**

1. In the old days (like 2005-2010-ish) there used to be several VCS: git, mercurial, and subversion (AKA SVN). However, at the time of this writing (December 28, 2023), the overwhelming number of projects use git. So learning VCS is pretty much synonymous to learning git. This is one less thing to worry about.

2. When I first started using Git I was _terrified_ that I would accidentally introduce a change that would just **wreck** a project and people would get mad at me and call me a n00b. Fortunately however, this didn't happen and almost certainly will not happen to you either, largely because of how VCS works. Changes can be rolled back, and most operations have very little potential for damaging impact. The exception for this is perhaps use of `reabse`, but this is not something that is usually needed, and even when it is the distributed nature of git makes unrecoverable mistakes unlikely. This is a **big worry** you do not need to have.

**BAD NEWS**

The learning curve for git/VCS is pretty steep, and some people find the prerequisites for even beginning this to be challenging in and of themselves (ie. basic understanding of computer file systems, installing software, the command line). 

That said, while it can be a struggle, there is no rush to learn any of this. Furthermore, once you get over the initial hurdles you'll find that you'll rarely need to perform any complex commands (at least 95% of my git usage centers around `git add`, `git commit` and `git push`).   

[Back to Home](README.md)
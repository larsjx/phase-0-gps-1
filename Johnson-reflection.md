### What git concepts were you struggling with prior to the GPS session?

I had been struggling with git feature branches. Specifically, before this GPS, I was having trouble with the deletion of my local feature branch after merging and deleting it on GitHub. I would receive errors in terminal like "git branch -D is required to force the branch's deletion" and I was reluctant to use force. I was also struggling with the use of git fetch and git merge.


### What concepts were clarified during the GPS?

During this GPS, I learned that I before attempting to delete my local feature branch, I should execute git checkout master followed by git pull origin master to ensure that my local master is up to date. After that it's no problem to delete my local feature branch with git branch -d <feature>. Our guide, Morgan, also explained the proper use of git fetch and git merge so I think I will be able to use them correctly in place of git pull origin master when needed.


### What questions did you ask your pair and the guide?

In addition to the items above, my pair (Kris) and I ended up asking for help in understanding merge conflicts and how to handle them. We initially struggled to create, edit and resolve the intentional merge conflict, but with some experimentation and patience we were able to complete the challenge.


### What still confuses you about git?

At this point, I think I have a reasonably good understanding of the git/GitHub core concepts. However, I really have to think about each step that I'm taking because the execution of these concepts is not yet second nature. For example, I believe I can now step through the creation and resolution of a merge conflict but I know it will be slow going until I have had considerably more practice.


### How was your first experience of pairing in a GPS?

My first experience of pairing in a GPS was excellent! I was fortunate that both Kris (my Pair) and Morgan (our Guide) were patient and supportive when I was unsure at different times. Kris has a naturally communicative style that was very helpful as she did a majority of the navigation and research this time around.

My only disappointment is that we were unable to completely finish all of the exercises in the time allotted. Fortunately, Kris and I were able to stay on and complete the challenge after Morgan signed off. This extra time with Kris was very helpful and gave us both some much needed practice in dealing with merge conflicts.
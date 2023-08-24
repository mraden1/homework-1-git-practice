
# Homework 1 - Git Practice

Hello, Class!

This is our first official assignment of the semester together, and it's going to be pretty easy. All I want you to do is create a text file, fill out some information, and use git from the command line to push your submission back up to Github! Consider this practice for your first coding project.

First, open this file in a raw text editor and observe its formatting. You should notice the heading *Homework 1 - Git Practice* above is actually just normal text preceded by a hash. This format is called [Markdown](https://www.markdownguide.org/), and is very useful because it is easily viewed in both a proper rendering engine and a regular text editor.

## What to Do - Part 1 - Push a New File

You can earn your grade for this assignment by doing the following:

1. Decide which operating system to use. For this particular assignment (not necessarily others), you may use your existing main operating system, provided you can get *ssh* and *git* for the command line installed. Otherwise, you'll want to follow our *Lab 00* class document to install a virtual instance of Ubuntu.

2. Read the entirety of our *Code Submission Guidelines* class document. Inside you'll learn more about [Markdown](https://www.markdownguide.org/) files and how to properly format them. Follow all the links and read all the external documentation.

3. Clone this repository to your local operating system somewhere. Again, you can choose your main operating system or a virtual Ubuntu, as long as you are able to use *ssh* and *git* for the command line. I recommend the main *Documents* folder in your account's home folder. If you're using Ubuntu, the *Documents* path will probably look like `/home/yourusername/Documents`. If you have cloned this repository correctly, you would see it as a sub-folder under the *Documents* diretcory (e.g., `/home/yourusername/Documents/homework-1/`).

4. Create a text file named README.md at the root of your repository. This might end up being a path similar to `/home/yourusername/Documents/homework-1/README.md`. Be careful to save the file with the correct extension: `md`.

5. Go back to the *Code Submission Guidelines* document and note the section entitled *README.md*. You'll find a snippet showing the expected format for *README.md* files you create for all your assignment submissions this semester (e.g., a heading with the assignment's title, a bulleted list with your full name + CWID + email, and so forth). Carefully observe the formatting and how it looks in the sample preview further down in the *Code Submission Guidelines* document.

6. Fill out your new *README.md* file with the same information as described in the previous step.

7. Using `git` from the command line, commit the changes to your local repository. You will find a tutorial for these commands in our *Code Submission Guidelines* document.

8. Push your changes to Github. You'll know you're successful when your repository on Github shows a nicely rendered version of your *README.md* file in your web browser. You may need to refresh the page after you perform pushes.

9. Pat yourself on the back because that was probably the hardest part of our assignment.

## What to Do - Part 2 - Gradescope Submission

This assignment utilizes an autograder from [Gradescope](https://www.gradescope.com/). Normally, you can submit your work directly from Github using Gradescope's web interface. However, this assignment's autograder needs to look at your *git* database directly, which Gradescope won't pull when using the Github submission method or drag-n-drop method.

1. Navigate to your main *Documents* folder, and find your repository inside.

2. Make a *zip* archive (not *tar.gz* or any other format) of your repository's entire folder.

3. Using the file upload submission method on Gradescope, drag-n-drop the archive you just made onto the upload widget. You should see a big list of files appear. Click the upload button and wait for Gradescope to grade your submission.

    * Unfortunately Gradescope (as of 2022-08-10) seems to have a quirk where most of the upload methods won't properly ingest your *git* database . This is why simply dragging-n-dropping your submission folder or using the Github upload method won't work for this particular assignment; You must specifically upload a zip file. Further assignments that won't need to inspect your *git* database will work with the other methods.

4. Carefully inspect all the output Gradescope gives you on the following page. It may seem confusing at first, but the autograder is giving you insight into how/where your submission has earned points and/or failed to earn points. Notice the right-hand side showing your earnings broken down by category.

## What to Do - Part 3 - Git Config

1. You most likely still haven't earned points for the "Git Config" category. Go find the output for that section further down the Gradescope results page, and note the autograder is trying to give you hints for how to earn more points. Specifically, the autograder wants you to correctly configure your *git* name and email address for further commits.

2. Go back to the *Code Submission Guidelines* page and find the *Git Config* section. Follow all the steps to properly configure your *git* name and email address for future commits.

3. Using the `git log` command (which can be exited with the `q` key), note that your previously configured name/email haven't been replaced in old commits. You'll need to make new commits to see your new configuration.

4. Make a new L1 section heading at the end of your *README.md* file, entitled My Thoughts. Inside the section, write a short paragraph describing how you're feeling today.

5. Save the file and perform another round of commit+push with *git*. Then use the `git log` command to confirm your latest commits now have your full name and institution email address.

6. Make another *zip* archive of your repo folder and re-submit to Gradescope.

7. Once again, inspect Gradescope's autograder output. If you've performed the previous steps correctly, you'll see you have more points than before. Specifically, the "Git Config" category shows full points. That's great!

## What to Do - Part 4 - Additional Commits

The last thing you need to do is rack up more commits in your *git* database. When using *git* to track changes to code, you typically want to make a commit whenever you make *significant progress* (not just when the work is completely finished). It's also important to accurately describe the commit itself. Commit messages like "Work", or "Made progress" usually won't make your future supervisors very happy. Instead, try to use descriptive messages like, "Fixed the xyz() function" or "Stop saving to the database when the user hits save, if nothing was actually changed".

For this part of the assignment, you just need to make something up. Write a paragraph explaining how you feel about your academic career so far, then commit it with *git*. Then write another paragraph describing your favorite movie, and commit it with *git*. Repeat this process until you have at least ten commits in your *git* database.

After making all your commits, don't forget to `git push` your changes to Github. Finally, re-submit to Gradescope and you should (hopefully) see you've received a perfect score.

## Parting Notes

Make sure you use *git* from the command line to both commit and push to Github. ***Do not manually upload files using the Github web interface***, and ***do not edit files directly on Github***. I can detect when someone does this, and will assign 0 points to the submission. The point here is to get a little more familiar with git from the command line and avoid falling victim to [Vendor lock-in](https://en.wikipedia.org/wiki/Vendor_lock-in).

Make sure your commit descriptions are specific. If you are caught using generic commit messages, you may lose points.

Also make sure your submission actually made it into Github and appears formatted correctly. If your submission isn't properly pushed to Github, your submission may only receive half credit. You can verify your pushes by viewing your submission file on Github's website. Github will detect the ".md" extension and attempt to render your *README.md* file properly. If it looks strangely different from your local copy, or from the expectations outlined in the *Code Submission Guidelines* document, you probably need to double check your work and try again. Remember: You can change+commit your local repo as often as you need; Just make sure to `git push` when you're done.






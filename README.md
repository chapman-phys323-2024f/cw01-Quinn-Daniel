# PHYS323 CW 01

**Author(s):** 
CHANGEME

## Specification

Complete the following exercises, saving your solutions in the indicated files. 

1. With your group, review the [git/GitHub Slides](https://slides.com/profdressel/git-overview) together and discuss.
1. Have each of your group members clone this repository (using SSH) into a directory on their own computer. Be sure to put the cloned repository inside another directory (like `PHYS323`) for organization. We will be cloning many classworks and homeworks this semester, so it's better to keep things tidy.
1. Using an appropriate editor (like Jupyter-lab), have one group member open the script `broken_script.py` then find the mistakes in the script and fix them. (Note: be sure to try running the script in the terminal with `python broken_script.py` in order to verify that it works.) Then have that group member save the file, `git add` the change to git, `git commit` the change (remember to use the flag `-m` to log a message directly on the command line), and `git push` it back to GitHub.
1. Have a different group member `git pull` the new fixed changes from GitHub into their cloned copy. Verify that the script now works in a terminal, then use `git move` the move file to a new name `fixed_script.py`. Add and commit this change to git, and push it to GitHub.
1. Have the original group member pull the new change from GitHub into their cloned copy. Have that group member change line 3 of the file to say `# This is a conflicting comment`. Save this change, add it to git, commit it, and push it to GitHub.
1. Have the _other_ group member also edit line 3 of the file _before pulling the new changes from GitHub_. Change line 3 to say `# This is a different conflicting comment`. Also change line 5 of the file to say `# This is an unrelated comment`. Save the file, add it to git, and commit it locally. Now have that same group member try to push the change to GitHub. What happens? Read the error messages carefully, as they tell you useful information.
1. Since the push fails, try pulling the new change from GitHub. What happens? Fix the "conflict" that occurs to your satisfaction, then add and commit the "merge" and "conflict resolution", and push the fix back to GitHub.

## Assessment

Analyze in this section what you found useful about this assignment in your own words. Include any lingering questions or comments that you may have. You can use the GitHub web interface to edit this file directly for now.

**CHANGEME**

## Honor Pledge

I pledge that all the work in this repository is my own with only the following exceptions:

* Content of starter files supplied by the instructor;
* Code borrowed from another source, documented with correct attribution in the code and summarized here.

Signed,

**YOURNAMES**

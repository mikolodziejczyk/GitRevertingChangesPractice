Reverting changes
---

You have GitRevertingChangesPractice. There're following commits:
• Initial - that adds first, second and third files.
• First_alter - that alters secondFile.txt and thirdfile.txt
• Second alter and remove - that removes firstFile.txt and alters secondfile.txt
• Third altering and adding - that alters secondfile.txt and adds fourthfile.txt

Clone the repository locally.

1. Reverting the last commit: Revert the last commit by creating another commit that reverts changes.
Revert changes into the staging area before commit.
Undo: Unstage the changes and discard changes from VSC.

Clone the repository locally.

2. Reverting to the specified commit: Revert all the changes back to the initial commit.
Which commit id do you specify when you are reverting?
Get the commit id from GitLens.
Check the results.
How do you revert with GitLens - overview?

Clone the repository locally.

3. Reset - what is the difference beween soft, mixed and hard?
What happens with the commit history?
What happens with files?
4. Can you do reset on branches pushed to the remote branches?

Assume that you have only local commits (as if the commits to remote didn't exist).
5. Reseting: Reset the state to the initial commit, discarding all the later commits - all added files should be removed.
6. Reseting into unstaged changes: The same, but you want the differences to be unstaged changes.
What will be the difference if you want to get the changes as staged ones?

Clone the repository locally.

7. Discarding changes
npm install jquery --save
Now you have the following unwanted changes:
to package.json - tracked file 
package-lock.json  - yet untracked file
to node_modules/jquery - untracked
Disarding the changes from the command line: Remove changes from the command line.
What happens with added files? 
What happens to ignored files?
Redo npm install jquery --save
Discarding changes from VSC: Use the source control pane to discard changes.

8. Restoring the specific file version
Restoring using command line: Restore the state of secondFile.txt from the initial commit.
What will be the file state?
Check whether all lines added in later commits disappeared.
Opening the specific file version with GitLens: Open the state of the thirdFile.txt from the initial commit.

9. Restoring accidentally deleted file
Restoring the file removed in later commits: Restore the firstFile.txt to the state from the initial commit.
Use command line.
Use syntax that specify the id  of the commit in which the file was actually deleted.
What would be the syntax difference if you specified the id of the previous commit?

Remove all folders.

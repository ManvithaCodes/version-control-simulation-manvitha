Reflection

During this SBA, I created a new GitHub repository and cloned it to my local machine using git clone. In my local repository, I created a new branch called feature/header. In that branch, I created an index.html file, wrote my code, staged the changes, and committed them. This helped me understand how we can write code in a separate branch without affecting the main branch. At first, I actually thought each branch would have its own separate HTML file saved on my computer, but then I realized Git keeps everything in the same file and just tracks different versions. That was something new for me and helped me understand how branching really works.

Next, I switched back to the main branch using git checkout -b main, because the GitHub repository was empty and didn’t have a main branch yet. From the main branch, I created another branch called feature/footer and added my footer code. After committing those changes, I switched back to the header branch and changed something in the footer section to create a conflict. When I merged the footer branch into main, it worked fine. But when I tried merging the header branch, I got a merge conflict. I resolved the conflict manually, completed the merge, and then pushed my final work to GitHub. This helped me understand how merge conflicts happen and how to fix them by reading the code carefully. I also created a Markdown file using the touch command and pushed it to GitHub.

Challenges and Solutions
1.	Merging the header file:
When the merge conflict error popped up, I was confused because I had never seen conflict markers before. I looked at both versions, chose what I wanted to keep, removed the markers, and saved the final version. This helped me understand conflicts better.

2.	Creating the main branch:
Since the GitHub repo was empty, there was no main branch. I learned that I had to create it locally before pushing, which helped me understand how local and remote branches connect.

Key Takeaways
•	Commit my work often so I don’t lose progress and can track what I did.
•	Always make sure I’m on the correct branch before creating new branches or making changes.
•	Write clear commit messages so I understand my changes later.
•	Create the main branch myself if it doesn’t exist in the remote repo.
•	Avoid changing code directly on main and use branches for all new work.


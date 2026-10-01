
* **Question 1:** `--global` sets your settings (like name and email) for every Git project on your entire computer. Omitting it applies the settings only to the current repository you are in.


* **Question 2:** It holds Git’s internal tracking data, configuration, commit history, and branches (such as `HEAD`, `config`, `objects`, `refs`, and `hooks`). The dot makes it a hidden folder.


* **Question 3:** Untracked files appear in red under the "Untracked files:" header in `git status`. They are files that exist in your folder but have never been added to Git yet.


* **Question 4:** The files listed inside `.gitignore` disappear from the "Untracked files" list, and `.gitignore` itself appears as the new untracked file.


* **Question 5:** Committing `.gitignore` shares the ignore rules with team members so everyone ignores the exact same junk files (like temporary files or builds).


* **Question 6:** It moves from the **Working Directory** (red, untracked/modified) to the **Staging Area** (green, "Changes to be committed"), and finally to the **Repository** (clean status) after committing.


* **Question 7:** It prints the branch name, the short commit hash, the commit message, and a summary line stating how many files changed and how many lines were inserted or deleted.


* **Question 8:** It is called the **short SHA** (or short hash). It serves as a unique short nickname/ID to identify that specific commit easily.


* **Question 9:**
1. Modify files (Work)
2. `git status` (Check changes)
3. `git add <file>` (Stage changes)
4. `git commit -m "message"` (Save snapshot)


* **Question 10:** A `README.md` is placed in the root folder of a project to introduce the project, explain what it does, and show how to install and run it.


* **Question 11:** It securely saves an authentication token on your machine so Git can reuse it automatically without asking for your password every time.


* **Question 12:** The `README.md` file. GitHub automatically formats and displays Markdown (`.md`) files on the repository landing page to give visitors an immediate overview.


* **Question 13:** It does not change your local commits at all; it simply copies them to the remote server and moves the remote tracking branch marker (e.g., `origin/main`) forward.


* **Question 14:** A **private repository** is backed up securely on GitHub’s cloud where only you and invited collaborators can access it. **No repository** means your code exists solely on your local computer with zero cloud backup or sharing.
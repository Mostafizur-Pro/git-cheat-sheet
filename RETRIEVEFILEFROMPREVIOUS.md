## Retrieve a File from a Previous Commit

To retrieve a file from a previous commit in your Git repository, follow these steps:

1. **Find the commit hash** that contains the version of the file you want. Use:

   ```bash
   git log --oneline
   ```

2. **Checkout the file from the specific commit** using:

   ```bash
   git checkout <commit_hash> -- <file_path>
   ```

   This command retrieves the version of the file from the specific commit and places it in your working directory.

3. **Optionally, commit the changes** if you want to keep the retrieved version:
   ```bash
   git add <file_path>
   git commit -m "Reverted <file_path> to version from <commit_hash>"
   git push origin <branch_name>
   ```

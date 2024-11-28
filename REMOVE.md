## Remove node_module / .env file from GitHub

To remove a file from your GitHub repository, follow these steps:

1. **Remove the file from your local repository** using the `git rm` command:

   ```bash
   git rm <file_path>
   ```

2. **Commit the changes** to your local repository:

   ```bash
   git commit -m "Removed <file_path>"
   ```

3. **Push the changes** to your remote GitHub repository:
   ```bash
   git push origin <branch_name>
   ```

If you want to remove the file from version control but keep it in your local file system, use:

```bash
git rm --cached <file_path>
`
```

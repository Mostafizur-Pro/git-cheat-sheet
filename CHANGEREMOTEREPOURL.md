## Change the Remote Repository URL

To change the remote repository URL in your Git repository, follow these steps:

1. **View the current remote URL** (optional):

   ```bash
   git remote -v
   ```

2. **Change the remote URL** using the `set-url` command:

   ```bash
   git remote set-url origin <new_url>
   ```

3. **Verify the change** (optional):
   ```bash
   git remote -v
   ```

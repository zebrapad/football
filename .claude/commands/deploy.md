# Deploy to Git & Vercel

Commit all changes, push to the feature branch, then deploy to Vercel.

## Steps

1. **Stage & commit** all modified/new files in /home/user/football:
   ```
   git add -A
   git commit -m "Deploy: <short description of changes>"
   ```
   If there is nothing to commit, skip the commit step and continue.

2. **Push** to the branch `claude/exciting-rubin-wkiwzv`:
   ```
   git push -u origin claude/exciting-rubin-wkiwzv
   ```

3. **Deploy to Vercel** using the Vercel MCP tool `mcp__Vercel__deploy_to_vercel`.
   - Project directory: `/home/user/football`
   - If the tool asks for a project name, use `football`

4. After the deploy succeeds, **report back** the Vercel preview URL so the user can open the game in the browser.

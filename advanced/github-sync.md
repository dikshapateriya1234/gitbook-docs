# Syncing with GitHub

GitBook's GitHub Sync keeps your docs and repository in perfect alignment.

## How Sync Works

GitBook watches your connected branch. When you push a commit to GitHub, 
GitBook updates automatically. When you edit in the GitBook editor, 
GitBook commits back to GitHub automatically.

## Setting Up Sync

1. Open your GitBook Space
2. Go to Settings using the gear icon at the bottom left
3. Click GitHub Sync
4. Choose your repository and branch
5. Select sync direction
6. Click Sync

## Sync Direction Options

- GitHub to GitBook: changes in GitHub update GitBook
- GitBook to GitHub: changes in GitBook update GitHub
- Bidirectional: changes in either place sync both ways

## Troubleshooting Sync Issues

| Problem | Solution |
|---------|---------|
| Pages not showing | Check they are listed in SUMMARY.md |
| Old content showing | Trigger a manual sync in Settings |
| Auth error | Re-authorize GitBook in GitHub settings |

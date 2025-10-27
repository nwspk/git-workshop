# Git Cheatsheet

## Basic Commands

### Check status
```bash
git status
```

### Create a new branch
```bash
git checkout -b your-branch-name
```

### Stage changes
```bash
git add filename.md
# or stage all changes:
git add .
```

### Commit changes
```bash
git commit -m "Your descriptive message here"
```

### Push to remote
```bash
git push origin your-branch-name
```

### Pull latest changes
```bash
git pull
```

## Workflow

1. Create branch: `git checkout -b feature-name`
2. Make changes
3. Stage: `git add .`
4. Commit: `git commit -m "Description"`
5. Push: `git push origin feature-name`
6. Open merge request in GitLab
7. Get review & merge!

## Merge Conflicts

If you see a merge conflict:
1. Don't panic! 🙂
2. Open the conflicted file
3. Look for conflict markers: `<<<<<<<`, `=======`, `>>>>>>>`
4. Decide which changes to keep
5. Remove the conflict markers
6. Stage and commit the resolved file

## Tips

- Commit early, commit often
- Write clear commit messages
- Pull before you push
- Branches are cheap - use them!
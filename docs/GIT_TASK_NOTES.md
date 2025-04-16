# Git Task Notes

## Branch Commands

```bash
git checkout -b dev
git checkout -b feature/terraform-docker
```

## Pull Request Strategy

- Feature → Dev → Main
- Pull requests created and merged via GitHub UI

## Tags

```bash
git tag -a v1.0 -m "Initial release"
git push origin v1.0
```

## Useful Commands

```bash
git status
git add .
git commit -m "message"
git log --oneline --graph --all
```

## Merge Conflict Fix

- Use `git status` to find conflicting files
- Manually edit them, then:
```bash
git add 
git commit
```

## Git Stash

```bash
git stash        # Save uncommitted changes
git stash apply  # Re-apply changes
```

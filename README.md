# Git Kata

## Instructions

You're expected to capture **your full shell history** while you're working on this, we're mostly interested in seeing your workings rather than the finished end result, so please annotate this with your thinking on what you're exploring and what you learn from the output each time.

- Locate and edit the commit with the credentials in and remove the credentials
- At some point a bug was introduced after `A`, locate and remove that commit, to test if the bug is present you can do:
```bash
curl -X POST -d "$(cat files/*)" https://69o349t9b2.execute-api.eu-west-2.amazonaws.com/production/
```
- Reorder the commits to be
  1. `initial commit`
  1. `add readme`
  1. `A`
  1. `B`
  1. `C`
  1. `D` (from branch `feature/other-branch`)
  1. `E`
  1. `F`
  1. `etc...`

## Expected outputs

- `shell_history.txt` - annotated shell history.
- `archive.zip` - archived zip of the full codebase including the `.git` directory
- `notes.txt` - any thoughts or notes you'd like to share with the assessor
- `web-history` - google/stackoverflow/etc is allowed but we do ask to see your history while you're working on it
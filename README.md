# SCCM4910 Teamwork

Starter repository for **Lab 4: Branches, Pull Requests and Merge Conflicts**.

## What is here

| File | Purpose |
|---|---|
| `greetings.py` | Add one greeting line below the marker, on a feature branch |
| `motto.txt` | Deliberately contains one line, so the conflict drill collides |
| `README.md` | This file |

## How to use it

Open the [module starter repository](https://github.com/wrwei/sccm4910-teamwork)
and **fork** it into your own GitHub account, then clone your fork.
Work in your own fork. You can review your own diff in the reviewer role
and record feedback in your notes, or exchange reviews with a willing
partner. Your PR targets your fork's main. Set your Git identity locally
in the new clone, as Task 1 shows.

### Open the PR in your own fork

In your fork, choose **Pull requests > New pull request**. GitHub may still
suggest `wrwei/sccm4910-teamwork` as the base repository. Before creating the
PR, check these four fields (replace `USERNAME` with your GitHub username):

| Field | Required value |
| --- | --- |
| Base repository | `USERNAME/sccm4910-teamwork` |
| Base branch | `main` |
| Head repository | `USERNAME/sccm4910-teamwork` |
| Compare branch | `add-USERNAME-greeting` |

Choose **compare across forks** if the repository selectors are hidden.
Both repository owners must be your account. You can open the comparison
directly by replacing both occurrences of `USERNAME` in this URL:

```text
https://github.com/USERNAME/sccm4910-teamwork/compare/main...add-USERNAME-greeting?quick_pull=1
```

If you already opened a PR against `wrwei/sccm4910-teamwork`, close it and
create a new PR in your fork. Your branch and commits are still there.

### Offline backup and local work

The ZIP is an optional offline backup. If GitHub is unavailable, extract
it and follow Task 1's local setup. Practise with local branches and review
notes, then complete the online fork/PR steps with a demonstrator when
access is restored.
Keep the hidden `.git` folder when saving your project.

Add your greeting **below the marker, with four spaces of indentation**.
Run the program before committing. Amend the practice message before
your first push; make a new commit for later review improvements.

## Run it

```bash
python3 greetings.py
```

## Note for staff

`motto.txt` must contain exactly the line `DevOps is about tools.` — the
Lab 4 conflict drill (Task 6) and the answer sheets quote it verbatim.
Keep these three files in the published starter and Moodle ZIP in sync.
Put the repository URL above next to the ZIP in Moodle. A short, readable
commit history is helpful; students count what is present rather than
expecting a fixed total.
No workflow or automatic CI checks are configured in this starter.

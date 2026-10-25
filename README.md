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

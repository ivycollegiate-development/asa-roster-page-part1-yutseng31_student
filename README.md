## Before you start — every session

You work on the class VS Code server, in your own clone of this repo.
Your userid shows up in your repo name, your clone URL, and your filenames
via `$(whoami)`: `whoami` prints your userid, and `$(whoami)` inserts it
automatically. If the folder is missing, re-clone it — your lesson has the exact
URL, always ending in `-<your-username>_student.git` (example:
`asa-roster-page-part1-cyen29_student.git`).

**Pull before work, every session** — it gets any changes I pushed to your
repo since last class:

```bash
cd ~/<your-clone-folder>
git config pull.rebase false
git pull
```

- `git config pull.rebase false` tells git how to combine work; run it once,
  it is not an error if you already ran it.
- If the pull prints `Already up to date.` you have everything.
- **Asked for a username/password?** GitHub username plus Personal Access
  Token (PAT) — never your GitHub password.

---

# asa-roster-page-part1 — your own repo

You received your OWN copy of this repo by accepting a GitHub invitation in
your email. Everyone in class has their own copy, so your work is yours alone.
Everything for the Teams
screen of our Basketball Stats App happens in this copy.

    03-roster-table/index.html   the roster page you build on
    03-roster-table/L03-Roster-Page-Part-1.md   today's lesson, step by step
    self_check.py                run this to check yourself: starts at 3 of 4 passing

Run:

    python3 self_check.py

Your job today: make all 4 checks pass, commit, and push. After every push
my grade bot runs the same checks and posts your score under the **Actions**
tab on github.com — green `4 of 4 checks passing` means you are done.

**First time on this machine?** Set your git identity (once):

```
git config --global user.name "Your Name"
git config --global user.email "yourusername_student@ivycollegiate.org"
```

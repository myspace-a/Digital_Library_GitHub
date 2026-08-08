# Week 2 — Learn branches, issues, and pull requests (simple steps)

Goal
- Practice creating a short-lived branch, add a file, open a Pull Request (PR), and merge it.
- Create a simple Issue Template and a quick-start doc so you can open and close issues.

How to use this week
- Work in small steps (10–30 minutes per session).
- Use the Dev branch as the main learning branch (do not change main or import).

Daily plan
Day 1 — Create the week file on a branch
  [x] Create a branch: start-week-02
  
  [x] Copy this template into docs/week-02.md and commit on start-week-02
  
  [x] Open a PR: base=Dev, compare=start-week-02
  
  [x] Merge the PR and delete start-week-02

Day 2 — Create an Issue Template
  [x] Add: .github/ISSUE_TEMPLATE/update-metadata.md
  
  [x] Include a short checklist for metadata fields (title, author, ISBN, tags)
  
  [x] Commit on a short-lived branch (e.g., issue-template-update) and open PR into Dev

Day 3 — Quick-start doc

  [x] Create docs/quick-start.md with 1 short paragraph: how to view files on GitHub and where to find the Learning Plan
  
  [x] Practice editing it in a branch and merging

Day 4 — Create labels and a sample issue
  [x] On GitHub: create labels: enhancement, bug, docs, help wanted
  
  [x] Create one issue titled "Update sample metadata" using the new template

Day 5 — Close an issue by making a change
  [x] Make a tiny change (for example, edit docs/quick-start.md)
  
  [x] Commit on a branch, open a PR, merge — then close the issue referencing the PR

Day 6 — Practice merging and resolving basic conflicts

  [x] Create two tiny branches that change different lines in the same file; merge them
  
  [x] If a conflict happens, practice resolving it in the web UI (follow instructions)

Day 7 — Review & prepare Week 3
  [ ] Write 3 short notes about what you learned
  
  [ ] Create docs/week-03.md from the week template (draft) and open a PR

What to expect after each action
- Creating a branch: saves your changes separately and keeps Dev unchanged.
- Opening a PR: shows the change and lets you review before merging.
- Merging: applies the change into Dev. If you delete the branch after merging, the history remains safe.

Suggested commit and PR text
- Commit message: "Add Week 2 plan: docs/week-02.md"
- PR title: "Week 2: Add docs/week-02.md"
- PR description: "Adds the Week 2 learning plan (docs/week-02.md). This is a small documentation file to guide tasks for the second week."

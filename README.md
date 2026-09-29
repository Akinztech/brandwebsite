# SIWES Project — Git & GitHub Team Workflow

## Team Rules

1. Do not work directly on the `main` branch.
2. Each team member must work on their assigned branch.
3. Always pull the latest changes before starting work.
4. Test your changes locally before committing.
5. Use meaningful commit messages.
6. Push your branch to GitHub.
7. Create a Pull Request into `main`.
8. The team lead reviews Pull Requests before merging.
9. Do not delete or overwrite another student's work without discussing it with the team.
10. If a merge conflict occurs and you are unsure how to resolve it, ask the team lead.

## Branches

* `main` — final/stable project
* `student-1` — Homepage - Veronica
* `student-2` — About Us - Stephen
* `student-3` — Solutions - Tunmise
* `student-4` — Contact Us - Damilola
* `student-5` — Blog & News - Motunrayo

## Daily Workflow

Before working:

```bash
git checkout main
git pull origin main
git checkout student-X
git merge main
```

Work on the assigned task and test it.

Then:

```bash
git status
git diff
git add .
git commit -m "Describe your changes"
git push
```

Create a Pull Request:

```text
student-X → main
```

Wait for the team lead to review and merge the Pull Request.

## Important

Never push directly to `main`.

Never use `git push --force` unless the team lead specifically instructs you to do so.

Always communicate with the team before making major changes to shared files.

# Git & GitHub

**Goal:** Track changes and collaborate safely.

## Key concepts

- **Repository:** project files and their history.
- **Commit:** a recorded change.
- **Branch:** an isolated line of work.
- **Pull Request (PR):** a proposed change for review.

## Practice

```bash
git clone https://github.com/OWNER/IEEE-RAS-AI-Knowledge-Base.git
cd IEEE-RAS-AI-Knowledge-Base
git checkout -b docs/my-first-update
# Edit a documentation file
git add .
git commit -m "docs: improve introduction"
git push -u origin docs/my-first-update
```

Replace `OWNER` with the actual GitHub user or organization. Open a PR from your branch into `main`.

## Exercise

Create a branch named `docs/your-name`, add one helpful sentence to a tutorial, and submit it for review.

**Checkpoint:** Explain why team members should not push directly to `main`.

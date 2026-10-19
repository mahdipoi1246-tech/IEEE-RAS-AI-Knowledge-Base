# IEEE RAS AI & Robotics Knowledge Base

A ready-to-run MkDocs Material documentation prototype combining a **Learning Hub** and **Projects Hub**.

## Run locally

Requires Python 3.10+.

```bash
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Open http://127.0.0.1:8000

## Validate

```bash
python -m mkdocs build --strict
```

## Deploy

1. Create a GitHub repository and push this project to `main`.
2. In repository **Settings → Pages**, set the source to **Deploy from a branch** and select `gh-pages` after the deployment workflow creates it.
3. The included GitHub Actions workflow builds and publishes on pushes to `main`.
4. If the repository or organization restricts Actions permissions, enable the minimum necessary workflow write permissions.

The website is not publicly deployed until you connect and configure a GitHub repository.

## Before public launch

- Obtain team approval and review branding usage.
- Verify Sumo hardware, code, and results.
- Replace placeholder repo links and assign maintainers.
- Check that all published information is public and authorized.

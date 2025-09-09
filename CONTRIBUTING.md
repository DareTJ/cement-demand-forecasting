The CONTRIBUTING.md file explains how we work together on this project.
Here’s what you need to know:

🚀 1. Workflow in 5 Steps

Clone the repo → git clone <repo-url>

Switch to dev → git checkout dev

Create a branch → git checkout -b feature/my-feature

Work, commit, push → git commit -m "feat: message" + git push origin feature/my-feature

Open a Pull Request (PR) into dev

🌿 2. Branch Rules

main → stable (don’t push here directly)

dev → where all features merge

feature/* → your work branches

fix/* → bug fixes

📊 3. Data Handling

Never commit raw or sensitive data

Store data in data/ (ignored in git)

Use DVC/Git LFS if configured

Check data/README.md for access instructions

🧑‍💻 4. Code & Notebooks

Keep reusable code in src/

Clear notebook outputs before committing

Follow PEP8 + use Black/isort for formatting

✅ 5. Testing

Add tests in tests/

Run tests locally:

pytest tests/


PRs must pass tests before merging

📥 6. Pull Requests

Always open PRs into dev

Fill in the PR checklist (style, tests, docs, no sensitive data)

At least one reviewer must approve

🐞 7. Issues

Use Issues for bugs, features, or tasks

Assign yourself before starting work

Link Issues in your PR (Fixes #12)

🔒 8. Security

Never commit secrets or .env files

Share only env.example with placeholders

📜 9. License & Citations

Respect the project license

Cite datasets/models in REFERENCES.md if used

💬 10. Communication

Use GitHub Issues/Discussions for collaboration

Contact maintainers if you’re stuck or need approvals


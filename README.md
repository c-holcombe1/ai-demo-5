# AIPP AI Terminology Icebreaker

A self-contained five-minute browser game for AIPP learners approximately 10 months into their Multiverse programme.

## What is included

- `index.html` – the complete game. All HTML, CSS and JavaScript are in this one file.
- `facilitator-guide.md` – a short run sheet and debrief prompts.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `aipp-ai-term-dash`.
2. Upload `index.html` and `facilitator-guide.md` to the top level of the repository.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`, then click **Save**.
7. After deployment, GitHub will show the live Pages URL. It normally follows this pattern:
   `https://YOUR-USERNAME.github.io/aipp-ai-term-dash/`

GitHub Pages can take a few minutes to publish after the first deployment.

## Run locally

Double-click `index.html`. No installation, server, libraries or internet connection are required after the file has been downloaded.

## Customise the questions

Open `index.html` in a text editor and find `const questions = [` near the bottom. Each question has:

- `level` – the difficulty label
- `q` – the question
- `a` – four answer choices
- `correct` – the zero-based answer position: `0` is the first choice, `1` the second, and so on
- `explain` – the explanation shown after the learner answers

Keep the total at around 10 questions for a five-minute session.

## Accessibility and privacy

- Works with keyboard navigation and visible focus states.
- Includes responsive layouts for phones and laptops.
- Respects reduced-motion settings.
- Collects no names, scores or personal data.
- Makes no external network requests and uses no cookies or analytics.

## Suggested delivery

Give learners exactly five minutes. Ask them to play independently, then use the final minute of the wider activity to discuss the question that caused the most uncertainty.

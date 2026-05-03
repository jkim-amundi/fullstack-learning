I'm building a learning project — a web dashboard backed by GitHub data. Stack: FastAPI + Jinja2 templates + vanilla HTML/JS + Chart.js (planned), deployed to Render free tier with auto-deploy from GitHub on push. Repo: fullstack-learning. I'm on Mac (will use Windows occasionally too); Python 3.13; venv in venv/.
What's already done:

main.py serves an HTML page at / and JSON at /api/health
templates/index.html has a button that fetches /api/health and displays the response
Deployed and live at https://fullstack-learning-j8q3.onrender.com
.gitignore, requirements.txt set up

The roadmap from here, one step at a time:

Add a GitHub API call (using httpx) — fetch my own public repos and display the list on the page
Add GITHUB_TOKEN as an environment variable (locally via .env, on Render via dashboard)
Add Chart.js and render one chart (e.g. commits per repo)
Add SQLite caching with a manual "Refresh" button (because data updates irregularly — anywhere from multiple times a day to weekly)
Add more charts and styling

Constraints / preferences:

I'm learning, so explain what's happening and why, especially when introducing new concepts
One step at a time, with local testing before pushing
Don't skip ahead even if it looks faster
I want to understand the stack, not have it done for me

Pick up at step 1. Before writing code, ask me anything you need (e.g. my GitHub username, which repos I want to show).
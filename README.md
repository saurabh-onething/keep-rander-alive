# Render Keep-Alive

A scheduled GitHub Action that pings the health endpoint of the PDF service on Render every 10 minutes, so the free-tier service doesn't go to sleep.

- Target: https://onething-pdf-service.onrender.com/health
- Schedule: every 10 minutes (`*/10 * * * *`). GitHub may delay scheduled runs by a few minutes.
- Manual run: Actions → "Keep Render PDF Service Awake" → Run workflow.

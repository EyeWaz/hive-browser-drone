# Hive browser drone (Scout)

A GitHub Actions Playwright drone for [The Hive](https://hive.rondgill.workers.dev/). It wakes every 5 minutes (and on demand), drives Chromium for public browsing, reports results back to the Hive, and can stream a live view when Ron asks.

**No secrets live in this repository.** `DRONE_KEY`, `GEMINI_API_KEY`, and `HIVE_URL` are Actions secrets only.

Skills: browse, research, writing, web-requests. It never posts outside the Hive and never acts as anyone's account unless Ron takes control of the live view.

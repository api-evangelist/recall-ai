---
title: "How to build a Zoom bot from scratch"
url: "https://www.recall.ai/blog/how-to-build-a-zoom-bot"
date: "2026-06-16"
author: "Aydin Schwartz"
feed_url: "https://www.recall.ai/blog"
---
This walkthrough builds a Zoom bot using browser automation with Playwright rather than Zoom's official Meeting SDK, parsing a Zoom URL, joining via the web client, scraping live captions, and mapping speaker avatars to participant names. The author notes scaling limitations such as each bot consuming roughly 500MB RAM and fragile UI selectors, highlighting why developers often choose managed APIs like Recall.ai instead.

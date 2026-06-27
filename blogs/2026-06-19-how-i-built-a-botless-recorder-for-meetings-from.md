---
title: "How I built a botless recorder for meetings from scratch"
url: "https://www.recall.ai/blog/how-i-built-a-botless-meeting-recorder-from-scratch"
date: "2026-06-19"
author: "Maggie Veltri"
feed_url: "https://www.recall.ai/blog"
---
Building a botless meeting recorder like Granola.ai requires solving interconnected engineering problems including audio capture, video recording, transcript generation, speaker attribution, and mute detection. The author found Electron sufficient to prototype but not to build a reliable recorder, ultimately creating a hybrid Electron/Swift architecture for Google Meet recording on macOS, with multitasking and tab-switching causing fragmented recordings that need post-processing.

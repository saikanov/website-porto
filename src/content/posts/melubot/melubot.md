---
title: Melu - Discord Bot Powered by LLM  
published: 2024-10-20
description: "Discord Bot with Function Calling"  
image: "./rcrop2.jpg"  
tags: ["Project", "Blogging", "LLM", "AIAPPS"]  
category: Guides  
draft: false  
---

> Cover image source: [Source](https://www.reddit.com/r/silverhair/comments/165q7tn/melusine_fatego/)

I’m online on Discord almost every day, typically for 12-15 hours. If sleep wasn’t a necessity, I’d be online 24/7! This consistent presence inspired me to build a chatbot for my personal use on Discord, and a few friends on my server have also started using it.

Initially, I built the bot using local LLMs like Ollama and Oogabooga, but I later switched to OpenAI after discovering Langchain. Running it locally had been ideal for privacy, and I managed to get it working. But my GPU struggled with heavier models like Llama 3.1, especially when I wanted to play games while friends used the bot!

To make it more efficient, I moved to the OpenAI API, using GPT-4o-mini as the default model. It’s affordable and even supports multimodal input. If you're interested in hosting a bot yourself, consider exploring [Groq](https://groq.com/pricing/) and [Anthropic (Claude)](https://www.anthropic.com/pricing#anthropic-api) for additional options.

The bot’s code is available in my repo if you’d like to try setting it up: [melu-bot on GitHub](https://github.com/saikanov/melu-bot)

::github{repo="saikanov/melu-bot"}


For a hands-on demo, feel free to join my Discord for bot testing: [Bot Testing Channel](https://discord.gg/wVF5GEp7)
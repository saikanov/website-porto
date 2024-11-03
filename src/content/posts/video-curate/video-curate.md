---
title: Video Curate Tools?
published: 2024-10-25 
description: "why video player software doesnt have this feature? i need to make it my self"  
image: "./cover.png"  
tags: ["Python", "Blogging", "Train Model", "Dataset"]  
category: Guides  
draft: false  
---

::github{repo="saikanov/videogen-dataset_curation_gui"}


The journey started from my early days as a Model Trainer for a Text2Video model.

### The Problem
When training or fine-tuning an AI, **what’s the most important part?** The dataset! "Garbage in, garbage out"—so we need high-quality data. Curating a dataset should be simple: play a video, decide if it’s good, delete it if it’s not, and move to the next one.

But here’s the catch: **there wasn’t a video player that lets you delete videos while streaming and automatically moves to the next one.** This flow is crucial for efficient dataset curation. For image datasets, plenty of software lets you delete and move on easily. But for videos, I couldn’t find anything like it.

### The Solution
I created my own tool using the VLC Python wrapper and a simple Python GUI with Tkinter. Now, I can curate videos as quickly as possible!

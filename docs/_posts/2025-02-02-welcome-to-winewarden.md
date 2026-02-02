---
layout: post
title: "Welcome to WineWarden"
date: 2025-02-02
author: S1BGr0up
tags: [announcement, release]
---

We're excited to announce the release of WineWarden, a comprehensive security sandbox for Windows games on Linux!

## What's New

After months of development, we're shipping:

- **Filesystem Virtualization** with mount namespaces and Landlock LSM
- **Network Monitoring** with full DNS packet parsing
- **Process Security** with wildcard pattern matching
- **Dynamic Trust Scoring** from 0-100
- **Interactive TUI Dashboard** with real-time monitoring

## Built By Gamers

This isn't some corporate security suite. We're Linux gamers who got tired of choosing between security and performance. Every feature was designed with the gaming experience in mind.

## Get Started

```bash
git clone https://github.com/S1b-Team/winewarden.git
cd winewarden
cargo build --release
winewarden init
winewarden monitor
```

Game without fear!

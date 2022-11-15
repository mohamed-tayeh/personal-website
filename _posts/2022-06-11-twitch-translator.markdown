---
layout: post
title: Twitch Translator Bot
date: 2022-06-11
description: Twitch chat bot for translation
img: twitchTranslator.webp
tags: [Project]
---

This is a translator chatbot that I use for [my stream] to communicate with viewers from different backgrounds where English is not their first language. It currently supports all languages supported by [Argos Translate] (open source translation model).

It is currently being used by over 130 streamers (including myself).

The source code is private to avoid forks.

Demo:

<div class="gif-container">
  <img src="../assets/gif/twitchTranslator.webp" alt="Twitch Translator" height="588px" width="244px"/>
</div>

### Technology used

```
Backend:
  - TypeScript
  - NodeJS
  - WebSockets
  - gRPC
  - Twurple Library (Twitch Helix API)
  - Object Oriented Programming Software Paradigm
Translation ML Model:
  - ArgosTranslate Open Source Model
Deployment:
  - Microservice Architecture
  - Docker
  - Digital Ocean
  - GitHub Actions
  - Nektos/act
```

[my stream]: https://www.twitch.tv/{{site.twitch}}
[argos translate]: https://github.com/argosopentech/argos-translate

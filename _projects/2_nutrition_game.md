---
layout: page
title: Nutrition Game
description: Gamified nutrition tracker with photo-based meal logging
importance: 2
category: work
---

A mobile app that turns healthy eating into a game. Snap a photo of a meal, a vision model estimates what is on the plate, and a scoring algorithm turns it into XP.

- Nutrients are normalized and combined into a health multiplier.
- The meal score does not depend on portion size, so eating more of a healthy food is not "gaming" the score.
- XP follows a logistic curve so progress stays rewarding without being easy to exploit.

**Stack:** React Native (Expo), FastAPI, PostgreSQL, vision LLM.

_Status: in development._

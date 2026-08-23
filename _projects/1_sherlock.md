---
layout: page
title: Sherlock
description: Detect cheating in multiple-choice exams
importance: 1
category: ml
related_publications: false
---

<a href="https://github.com/kmangal/sherlock">github.com/kmangal/sherlock</a>

In India, cheating in high stakes exams is an endemic problem. Usually, when there is evidence of cheating, the whole exam is cancelled, at significant social cost. The goal of this project is to identify individual cheaters, while also building a system that is resistant to corruption in its own right.

Sherlock is an open source tool that is designed for this setting. It uses just the answer string as the feature space, to avoid creating new data pipelines that could compromise security. The algorithm uses Expectation Maximization to estimate the probability of observing unusually similar answer strings across candidates, and then aggregates that information while controlling false discovery rates.

---
aliases:
  - "2024336151653"
tags:
  - anthropic
  - github
  - source
  - screenshot
related: 
url: https://github.com/anthropics/prompt-eng-interactive-tutorial
---

# API Documentation

- [Text Completion API (legacy)](https://docs.anthropic.com/en/api/complete)
- [Messages API](https://docs.anthropic.com/en/api/messages)

## Messages

Calling the Messages API requires the following:

- `model`: the name of the model you intend to call
- `max_tokens`: the maximum number of tokens to generate before stopping
- `messages`: an array of alternating `user` and `assistant` messages
	- each message must be an object with a `role` and `content`
	- messages must start with a `user` turn

![[ScreenFloat Shot of Obsidian at Dec 1, 2024 at 16_34_33.png]]

## System Prompts

A System prompt provides context, instructions, etc to #claude  before presenting it with a question or task:

- system prompts exist outside of messages

# Role Prompting

- #claude has no context aside from what you tell it, and giving it instructions in inhabit a specific role improve's it's performance
  
![[ScreenFloat Shot of Obsidian at Dec 1, 2024 at 23_35_10.png]]



***

up:: 
back:: 
forward:: 
layer:: [[layer-099]]

***

year:: [[timeblock-year-2024|2024]]
quarter:: [[timeblock-quarter-4|Q4]]
month:: [[timeblock-month-12|December]]
week:: [[timeblock-week-48|W48]]
date:: [[timeblock-date-Dec01|Dec 01]]
day:: [[timeblock-weekday-7|Sunday]] ([[timeblock-monthday-01|1st]])
hour:: [[timeblock-hour-15|H15]]

***

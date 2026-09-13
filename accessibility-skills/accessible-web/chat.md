---
id: accessibility-skills-web-chat
title: "Chat"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/chat/
---

[Source material](https://www.atomica11y.com/accessible-web/chat/)

# Web Chat skills



## How to test a chat 

Given that I am on a screen with a chat

### 1. Keyboard only

- WHEN I use the arrow key to browse to the chat

  - I SEE the chat scrolls into view

- THEN when I use the tab key
 
  - I SEE individual controls are focusable in meaningful order (but not the chat itself)

- WHEN  I use the chat
 
  - I SEE notifications when a new message is received


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse to the chat

  - I HEAR the chat purpose is clear

  - I HEAR controls in the chat use appropriate roles like button, text field, etc.

  - I HEAR status changes (ex: user is typing…) are announced

  - I HEAR chat is intuitive to discover, open, close

- THEN when I use the tab key
 
  - I HEAR individual controls are focusable in meaningful order (but not the chat itself)

- WHEN  I use the chat
 
  - I HEAR notifications when a new message is received


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to a chat

  - I HEAR the chat purpose is clear

  - I HEAR controls in the chat use appropriate roles like button, text field, etc.

  - I HEAR status changes (ex: user is typing…) are announced

  - I HEAR chat is intuitive to discover, open, close

- WHEN  I use the chat
 
  - I HEAR notifications when a new message is received


### 4. Device settings

- WHEN I use custom font settings I SEE text resizes up to 200% without losing information


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Chat

Chat usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use chat to immediately communicate with a person, AI assistant, or automated service without leaving the current page.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a chat more effectively.

- Do not place chat controls at the end of the DOM where they become difficult to discover.


### Chat misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a chat. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Third-party chat widgets are not always natively accessible out-of-the-box.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13
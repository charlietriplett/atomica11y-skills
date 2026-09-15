---
id: accessibility-skills-web-pagination
title: "Pagination nav"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/pagination/
---

[Source material](https://www.atomica11y.com/accessible-web/pagination/)

# Web Pagination nav skills



## How to test a pagination nav 

Given that I am on a screen with a pagination nav

### 1. Keyboard only

- WHEN I use the arrow keys to browse to a pagination navigation

  - I SEE the nav comes into view

- THEN when I use the tab key to move focus to a link in the nav and use the enter key
 
  - I SEE my browser goes to the intended location


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow keys to browse to a pagination navigation

  - I HEAR the pagination nav has a logical name (&quot;pagination&quot;)

  - I HEAR the nav landmark is discoverable with screenreader shortcuts

- THEN when I use the tab key to move focus to a link in the nav and use the enter key
 
  - I HEAR my browser goes to the intended location


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to elements in the nav

  - I HEAR the pagination nav has a logical name (&quot;pagination&quot;)

  - I HEAR the nav landmark is discoverable with screenreader shortcuts

- THEN when I doubletap with the link in focus
 
  - I HEAR my browser goes to the intended location


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Pagination nav

Pagination nav usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use pagination to divide large collections of content into manageable, sequential pages.
- Use pagination when content is too long to reasonably display on a single page.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a pagination nav more effectively.

- Do not rely on color alone to indicate the current page; include aria-current=”page” to programmatically identify the current page.


### Pagination nav misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a pagination nav. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Infinite scroll is not inherently more usable; pagination provides clearer orientation and recovery.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15
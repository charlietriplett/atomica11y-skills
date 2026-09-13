---
id: accessibility-skills-web-breadcrumbs
title: "Breadcrumb navigation"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/breadcrumbs/
---

# Web Breadcrumb navigation skills



## How to test a breadcrumb navigation 

Given that I am on a screen with a breadcrumb navigation

### 1. Keyboard only

- WHEN I use the tab key to move focus to a link

  - I SEE focus is strongly visually indicated

- THEN when I use the enter key to activate the link
 
  - I SEE my browser goes somewhere


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a link

  - I HEAR the link names correspond to their destination page titles

  - I HEAR links identify as a links in a breadcrumb navigation landmark

  - I HEAR the current page link is indicated when focused

  - I HEAR is discoverable with screenreader shortcuts as a navigation landmark

- THEN when I use the enter key to activate the link
 
  - I HEAR my browser goes somewhere


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a link

  - I HEAR the link names correspond to their destination page titles

  - I HEAR links identify as a links in a breadcrumb navigation landmark

  - I HEAR the current page link is indicated when focused

  - I HEAR is discoverable with screenreader shortcuts as a navigation landmark

- THEN when I doubletap with the link in focus
 
  - I HEAR my browser goes somewhere


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Breadcrumb navigation

Breadcrumb navigation usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use breadcrums to provide clear navigation to assist in understanding a page’s location within a website.
- Use breadcrumbs to show the hierarchy of pages and allow users to navigate back to previous sections easily.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a breadcrumb navigation more effectively.

- Do not display application browsing history as breadcrumbs.
- Do not use overly complex or non-standard breadcrumb structures that confuse users.


### Breadcrumb navigation misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a breadcrumb navigation. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Breadcrumbs are unnecessary if the website has a search bar. Breadcrumbs serve a different purpose by providing context and hierarchy.
- Breadcrumbs are only useful for large websites. Even small websites can benefit from breadcrumbs for better navigation.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13
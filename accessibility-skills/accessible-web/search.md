---
id: accessibility-skills-web-search
title: "Search input"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/search/
---

[Source material](https://www.atomica11y.com/accessible-web/search/)

# Web Search input skills



## How to test a search input 

Given that I am on a screen with a search input

### 1. Keyboard only

- WHEN  I use the tab key to move focus to a search input
 
  - I SEE focus is strongly visually indicated

- THEN when I use the tab key to move focus to the search submit button
 
  - I SEE the button is focused

- THEN when I use the enter or spacebar key
 
  - I SEE the search results are presented


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use screen reader landmark shortcuts

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a search input

  - I HEAR the form itself is discoverable with screenreader shortcuts as search form or landmark

- WHEN  I use the tab key to move focus to a search input
 
  - I HEAR focus is strongly visually indicated

- THEN when I use the tab key to move focus to the search submit button
 
  - I HEAR the button is focused

- THEN when I use the enter or spacebar key
 
  - I HEAR the search results are presented


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a search input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a search input

  - I HEAR the form itself is discoverable with screenreader shortcuts as search form or landmark


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Search input

Search input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a search input form to let users immediately find specific content within the site or application.
- Wrap the input in a form with <code class="language-plaintext highlighter-rouge">role="search"</code> to make it easily discoverable via screen reader landmarks.
- Use a search form to group search inputs and related controls.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a search input more effectively.

- Do not omit a submit button after the search field.
- Do not force users to rely solely on the Enter key to submit a search.
- Do not force users to guess what the search context is. If it only searches a particular context, name the search accordingly like Search brands.


### Search input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a search input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A search input is not implicitly understood by a visual magnifying glass icon. A search input must be identifiable programmatically with an accessible name and a search role in the surrounding form,.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15
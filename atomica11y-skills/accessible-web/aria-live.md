---
id: atomica11y-skills-web-aria-live
title: "Dynamic single page app"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/aria-live/
---

[Source material](https://www.atomica11y.com/accessible-web/aria-live/)

# Web Dynamic single page app skills



## How to test a dynamic single page app 

Given that I am on a screen with a dynamic single page app

### 1. Keyboard only

- WHEN I use the application AND whole new dynamic page appears

  - I SEE browsing and focus starts consistently at top of new page content or top of page

- THEN when I use the tab key
 
  - I SEE focus starts consistently at the first interactive element in the new page content or top of page


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the application AND whole new dynamic page appears

  - I HEAR new content is announced or indicated 

  - I HEAR browsing and focus starts consistently at top of new page content or top of page

- THEN when I use the tab key
 
  - I HEAR focus starts consistently at the first interactive element in the new page content or top of page


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use the application AND new dynamic content page appears

  - I HEAR new content is announced or indicated 

  - I HEAR browsing and focus starts consistently at top of new page content or top of page


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Dynamic single page app

Dynamic single page app usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use an element with an aria-live=”polite” attribute for content that the screenreader expects to change.
- When main content updates, place focus deliberately and consistently at the top of new page content or the top of the HTML page. Choose one, but not both. Maintain predictability and orientation for the user.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a dynamic single page app more effectively.

- Do not wrap the entire page with an aria-live attribute. Persistent elements like navigation, filters or other controls shouldn’t be included.
- Avoid using aria-live=”assertive” as it is intended to interrupt and override every other message from the screenreader.


### Dynamic single page app misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a dynamic single page app. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- aria-live does not work consistently across screen readers, platforms and browsers. Some differences are to be expected.
- Dynamic content being read twice does not constitute a bug.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16
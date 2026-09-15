---
id: atomica11y-skills-web-image
title: "Informative image"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/image/
---

[Source material](https://www.atomica11y.com/accessible-web/image/)

# Web Informative image skills



## How to test an informative image 

Given that I am on a screen with an informative image

### 1. Keyboard only

- WHEN I use the arrow keys to browse to an image

  - I SEE the image comes into view


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow keys to browse to an image

  - I HEAR the content of the image alt text is clear (ignored if decorative)

  - I HEAR it identifies its role as an image or graphic (ignored if decorative)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to an image

  - I HEAR the content of the image alt text is clear (ignored if decorative)

  - I HEAR it identifies its role as an image or graphic (ignored if decorative)


An informative image must meet WCAG principles:

### 1. Perceivable

- All non-text content that is presented to the user has a text alternative that serves the equivalent purpose, unless it is decorative or repetitive
- If an image contains text critical to understanding the page the user has a text alternative that serves the equivalent purpose

## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Informative image

Informative image usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use informative images when the image conveys information not available in nearby text.
- Provide alternative text that communicates the image’s purpose or meaning.
- Keep alternative text concise and focused on what users need to know.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a informative image more effectively.

- Do not describe every visual detail when only the meaning matters.
- Do not duplicate adjacent text unless the image adds unique information.
- Do not use file names, generic labels, or image formats as alternative text.
- Do not use <code class="language-plaintext highlighter-rouge">aria-label</code> instead of <code class="language-plaintext highlighter-rouge">alt</code> for <code class="language-plaintext highlighter-rouge">&lt;img&gt;</code> elements. An <code class="language-plaintext highlighter-rouge">alt</code> attribute is required to be valid markup.


### Informative image misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a informative image. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Alternative text is not a visual description exercise. Alt text should describe the meaning of the image as it adds meaning to the page.
- Good alternative text communicates purpose, not everything visible in the image.
- A lifestyle brand image is not decorative. It conveys the people, values, aspirations, or experiences associated with the brand.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15
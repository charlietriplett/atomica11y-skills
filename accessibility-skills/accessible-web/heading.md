---
id: accessibility-skills-web-heading
title: "Heading: h1, h2, h3"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/heading/
---

[Source material](https://www.atomica11y.com/accessible-web/heading/)

# Web Heading: h1, h2, h3 skills



## How to test a heading: h1, h2, h3 

Given that I am on a screen with a heading: h1, h2, h3

### 1. Keyboard only

- WHEN I use the arrow key to browse to a heading

  - I SEE the heading comes into view

- WHEN  I use the tab key
 
  - I SEE nothing happens to the heading because headings must NOT be focusable


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse to a heading

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a heading and its level

  - I HEAR it is logically ordered, starting with a single h1, sections titled by h2, and sub-subsections with h3

- WHEN  I use the tab key
 
  - I HEAR nothing happens to the heading because headings must not be focusable


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to a heading

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a heading and its level

  - I HEAR it is logically ordered, starting with a single h1, sections titled by h2, and sub-subsections with h3


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Heading: h1, h2, h3

Heading: h1, h2, h3 usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use headings to create a clear and logical structure for your content.
- Use headings to define sections and subsections, ensuring proper hierarchy (e.g., h1 for the main title, h2 for sections, h3 for subsections).
- Ensure headings are descriptive and convey the purpose of the content they introduce.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a heading: h1, h2, h3 more effectively.

- Do not skip heading levels (e.g., jumping from h1 to h3) as it disrupts the logical structure.
- Do not use headings purely for styling purposes. Use CSS for visual presentation while maintaining semantic HTML.
- Do not overload headings with too much information, making them difficult to understand or navigate.
- Do not use headings as interactive elements. Headings should not be focusable or clickable, but can contain links.


### Heading: h1, h2, h3 misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a heading: h1, h2, h3. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Headings are not just for visual styling; they are critical for accessibility and content structure.
- Headings do not require additional roles or attributes unless using non-semantic elements (e.g., <code class="language-plaintext highlighter-rouge">div</code> with <code class="language-plaintext highlighter-rouge">role="heading"</code> and <code class="language-plaintext highlighter-rouge">aria-level</code>).
- Headings are not a replacement for proper navigation landmarks. Use headings alongside landmarks for a complete accessibility solution.
- While technically when there are multiple article elements, each one can have an h1, don’t do that. This is not helpful for people using a screen reader who are expecting a singular h1 to convey the purpose of the page as a whole.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15
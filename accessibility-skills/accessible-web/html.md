---
id: accessibility-skills-web-html
title: "Web HTML page"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/html/
---

[Source material](https://www.atomica11y.com/accessible-web/html/)

# Web Web HTML page skills



## How to test a Web HTML page 

Given that I am on a screen with a web html page

### 1. Keyboard only

- WHEN I use the keyboard to open a new web page

  - I SEE the page has a unique logical title in the browser tab


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the keyboard to open a new web page

  - I HEAR the page has a unique logical title in the browser tab

  - I HEAR landmarks and forms are discoverable with screenreader shortcuts


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to enter from the web browser tabs

  - I HEAR the page has a unique logical title in the browser tab

  - I HEAR landmarks and forms are discoverable with screenreader shortcuts

- THEN when I change orientations
 
  - I HEAR content is accessible in landscape or portrait orientation


### 4. Device settings

- WHEN I use text-sizing I SEE text can resize up to 200% without losing information

- WHEN I use orientation I SEE content is accessible in landscape or portrait orientation

- WHEN I use browser zoom I SEE content zooms up to 400% without horizontal scrolling


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Web HTML page

Web HTML page usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a Web HTML page to deliver accessible content.
- Use semantic landmarks (Header, Nav, Main, Footer) to structure the page logically.
- Ensure each page has a unique and descriptive title encoded in the head.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a web html page more effectively.

- Do not disable pinch-to-zoom or text resizing capabilities.
- <table>
  <tbody>
    <tr>
      <td>Do not use the pipe character (</td>
      <td>) as a divider in the page title.</td>
    </tr>
  </tbody>
</table>


### Web HTML page misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a web html page. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- The page title is not just for SEO. It is the first thing announced by a screen reader and is critical for distinguishing between multiple open tabs.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13
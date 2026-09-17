---
id: atomica11y-skills-ios-heading
title: "Heading"
description: Test accessible iOS Heading\". Use when a title introduces a page or section of content.
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-ios/heading/
---

[Source material](https://www.atomica11y.com/accessible-ios/heading/)

# iOS Heading skills



## How to test a heading 

Given that I am on a screen with a heading

### 1. Keyboard only

- WHEN I use the arrow key to browse to a heading

  - I SEE the heading comes into view

- THEN when I use the ctrl + tab key
 
  - I SEE nothing happens because headings must NOT be focusable


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to browse to a heading

  - I HEAR its purpose is clear and matches visible content

  - I HEAR it identifies itself as a heading

  - I HEAR (if heading levels are used) it is logically structured

- THEN when I the ctrl + tab key
 
  - I HEAR nothing happens because headings must not be focusable


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17
---
id: accessibility-skills-web-toast-snackbar
title: "Toast snackbar"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/toast-snackbar/
---

# Web Toast snackbar skills



## How to test a toast snackbar 

Given that I am on a screen with a toast snackbar

### 1. Keyboard only

- WHEN I use use features that trigger the toast

  - I SEE the toast (BUT focus DOES NOT transfer automatically when the alert appears)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use use features that trigger the toast

  - I HEAR the toast is read when it appears (but focus does not transfer automatically when the toast appears)

  - I HEAR it identifies itself as an alert or status when it appears

  - I HEAR if it is possible to close the toast, focus then returns to a logical place in the page

  - I HEAR it remains open until closed by user


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use features that trigger the toast snackbar

  - I HEAR the toast is read when it appears (but focus does not transfer automatically when the toast appears)

  - I HEAR it identifies itself as an alert or status when it appears

  - I HEAR if it is possible to close the toast, focus then returns to a logical place in the page

  - I HEAR it remains open until closed by user


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Toast snackbar

Toast snackbar usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Try not to use toast snackbars. But if you must, minimize its destructive potential.
- Use a toast to provide brief, non-interruptive feedback about an action (e.g., “Settings saved”).


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a toast snackbar more effectively.

- Do not automatically move keyboard focus to the toast when it appears.
- Do not put mission-critical or destructive actions inside a toast that disappears automatically.
- If a toast requires a user action (like an undo button), it crosses the boundary into needing to be an alert dialog.


### Toast snackbar misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a toast snackbar. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Toasts that disappear quickly are often missed by people with cognitive differences or people with low vision using screen magnifier; interactive toasts must persist until intentionally dismissed.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13
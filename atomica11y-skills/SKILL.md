---
name: atomica11y-skills
description: Evaluate, test, audit, or review design, web, iOS, and Android components using platform-specific accessibility criteria. Use when a task needs manual accessibility assessment and a component reference is available.
license: Apache-2.0
metadata:
  author: Charlie Triplett LLC
  version: "1.0.0"
  source_repository: "https://github.com/charlietriplett/atomica11y"
---

# Accessibility Manual Testing Component Index

## Scope of Application

This document applies **only** to tasks involving the evaluation, testing, auditing, or review of accessibility components across the following platforms:
- **UI Design** (static review context)
- **Android**
- **iOS**
- **Web**

### When This Skill Applies
Use this guide when:
- You are asked to evaluate, test, audit, or review an accessibility component.
- You need to ensure compliance with platform-specific accessibility standards.

### When This Skill Does Not Apply
This guide is **not**:
- A general-purpose implementation guide.
- A WCAG conformance claim.
- A substitute for platform-specific testing or automated-only testing.
- Applicable to unsupported components or cross-platform extrapolation.

### Required Inputs
Before beginning an assessment, you must have:
1. **Platform**: The target platform (e.g., Web, Android, iOS, or Design).
2. **Component**: The specific component to be assessed.
3. **Reference**: The implementation or design reference.
4. **Test Environment**: The available tools and environments for testing.

If any of these inputs are ambiguous, **ask for clarification** rather than infer.

### Strict Platform Guardrails (Mandatory Check)
Before accessing any component:
- **Verify the platform**: Confirm the target platform (Design, Android, iOS, or Web).
- **Isolate criteria by platform**: Never apply iOS guidelines to Web components, nor apply Web standards to native mobile apps.
- **State the context**: Explicitly declare the platform and component being assessed.

### Select the Component Reference
This is the registered skill. The platform and component documents in the directories below are reference material for this skill, not separately registered skills.

1. Select the directory for the confirmed platform: `accessible-design/`, `accessible-web/`, `accessible-ios/`, or `accessible-android/`.
2. Read the file named for the confirmed component, for example `accessible-web/button.md`.
3. If that file does not exist, mark the assessment as **Blocked**. Do not substitute criteria from another platform or component.

### Design vs. Functional Testing
- **Design Review**: Applies to static design evaluations. Behavioral test methods do not apply.
- **Functional Testing**: Applies to implemented components on Android, iOS, or Web.

### Out-of-Scope Cases
- Unsupported components.
- Automated-only testing without manual verification.
- Claims based on incomplete evidence.

## Assessment Workflow

### Scope Decision
Before starting, confirm:
- The platform, component, and test environment.
- Whether the task is eligible for assessment. If not, mark it as **Blocked**.

### Required Assessment Output
For each component assessment:
1. State the platform, component, and skill file used.
2. Report every check as **Pass**, **Fail**, or **Blocked**.
3. Record the exact test method and evidence for each result.
4. List unavailable environments as **Blocked**.

Use this format:

### Assessment

- Platform: Web
- Component: Button
- Skill: `accessible-web/button.md`

### Results

| Check                 | Status  | Evidence                                  | Remediation                          |
|-----------------------|---------|-------------------------------------------|--------------------------------------|
| Keyboard activation   | Pass    | Enter and Space activate the control      | N/A                                  |
| Accessible name/role  | Fail    | Screen reader announces "button" only     | Provide an accessible name           |
| Focus visibility      | Blocked | Keyboard testing environment unavailable  | Test with keyboard-only navigation   |
## Skills Platform Directory

### Accessible web

- [Alert notification](accessible-web/alert.md)
- [Animation](accessible-web/animation.md)
- [Dynamic single page app](accessible-web/aria-live.md)
- [Breadcrumb navigation](accessible-web/breadcrumbs.md)
- [Button](accessible-web/button.md)
- [Card box](accessible-web/card.md)
- [Carousel slideshow](accessible-web/carousel.md)
- [Chat](accessible-web/chat.md)
- [Checkbox](accessible-web/checkbox.md)
- [Date picker dialog](accessible-web/date-picker.md)
- [Dialog alert](accessible-web/dialog-alert.md)
- [Dialog modal](accessible-web/dialog-modal.md)
- [Dialog sheet](accessible-web/dialog-sheet.md)
- [Expander accordion](accessible-web/expander.md)
- [FAQ](accessible-web/faq.md)
- [Maps, charts & graphics](accessible-web/figure.md)
- [Filter](accessible-web/filter.md)
- [Footer / contentinfo landmark](accessible-web/footer.md)
- [Footnote](accessible-web/footnote.md)
- [Form](accessible-web/form.md)
- [Header / banner landmark](accessible-web/header.md)
- [Heading: h1, h2, h3](accessible-web/heading.md)
- [Hint, help, or error](accessible-web/hint-help-error.md)
- [Web HTML page](accessible-web/html.md)
- [iframe](accessible-web/iframe.md)
- [Decorative image / icon](accessible-web/image-decorative.md)
- [Informative image](accessible-web/image.md)
- [Number input](accessible-web/input-number.md)
- [Text input](accessible-web/input-text.md)
- [Link](accessible-web/link.md)
- [List](accessible-web/list.md)
- [Autocomplete input with listbox](accessible-web/listbox-autocomplete.md)
- [Main landmark](accessible-web/main.md)
- [Nav popover button](accessible-web/nav-popover.md)
- [Navigation landmark](accessible-web/nav.md)
- [Pagination nav](accessible-web/pagination.md)
- [Password input](accessible-web/password-input.md)
- [Popover](accessible-web/popover.md)
- [Progress indicator](accessible-web/progress.md)
- [Radio button](accessible-web/radio.md)
- [Range slider input](accessible-web/range-slider.md)
- [Scrolling container](accessible-web/scrolling-container.md)
- [Search input](accessible-web/search.md)
- [Region section landmark](accessible-web/section-region.md)
- [Select dropdown listbox](accessible-web/select.md)
- [Separator / horizontal rule](accessible-web/separator.md)
- [Skip link](accessible-web/skip-link.md)
- [Star rating input](accessible-web/star-rating.md)
- [Stepper input](accessible-web/stepper-input.md)
- [Sticky element](accessible-web/sticky-content.md)
- [Strikethrough content](accessible-web/strikethrough.md)
- [Table](accessible-web/table.md)
- [Tab group](accessible-web/tabs.md)
- [Textarea multiline input](accessible-web/textarea.md)
- [Toast snackbar](accessible-web/toast-snackbar.md)
- [Toggle switch](accessible-web/toggle-switch.md)
- [Tooltip](accessible-web/tooltip.md)
- [Video/audio player](accessible-web/video-audio.md)

### Accessible design

- [Alert notification](accessible-design/alert.md)
- [Android app view](accessible-design/android-view.md)
- [Animation & motion](accessible-design/animation.md)
- [Audio player](accessible-design/audio.md)
- [Breadcrumb navigation](accessible-design/breadcrumbs.md)
- [Button](accessible-design/button.md)
- [Card box](accessible-design/card.md)
- [Carousel slideshow](accessible-design/carousel.md)
- [Checkbox](accessible-design/checkbox.md)
- [Dialog modal](accessible-design/dialog-modal.md)
- [Expander accordion](accessible-design/expander.md)
- [Maps, charts & graphics](accessible-design/figure.md)
- [Footer landmark](accessible-design/footer.md)
- [Form](accessible-design/form.md)
- [Header landmark](accessible-design/header.md)
- [Heading: h1, h2, h3](accessible-design/heading.md)
- [Web HTML page](accessible-design/html.md)
- [Decorative image / icon](accessible-design/image-decorative.md)
- [Informative image](accessible-design/image.md)
- [Number input](accessible-design/input-number.md)
- [Text input](accessible-design/input-text.md)
- [iOS app view](accessible-design/ios-view.md)
- [Link](accessible-design/link.md)
- [Nav menu button](accessible-design/nav-button.md)
- [Navigation landmark](accessible-design/nav.md)
- [Popover](accessible-design/popover.md)
- [Radio button](accessible-design/radio.md)
- [Search form](accessible-design/search.md)
- [Select dropdown](accessible-design/select.md)
- [Tab group](accessible-design/tabs.md)
- [Textarea multiline input](accessible-design/textarea.md)
- [Toggle switch](accessible-design/toggle-switch.md)
- [Tooltip](accessible-design/tooltip.md)
- [Video player](accessible-design/video.md)

### Accessible android

- [Badge](accessible-android/badge.md)
- [Bottom app bar](accessible-android/bottom-app-bar.md)
- [Floating action button](accessible-android/button-floating.md)
- [Icon button](accessible-android/button-icon.md)
- [Button](accessible-android/button.md)
- [Card](accessible-android/card.md)
- [Carousel](accessible-android/carousel.md)
- [Checkbox](accessible-android/checkbox.md)
- [Chips](accessible-android/chips.md)
- [Date picker](accessible-android/date-picker.md)
- [Full screen dialog](accessible-android/dialog-full-screen.md)
- [Basic dialog](accessible-android/dialog-modal.md)
- [Heading](accessible-android/heading.md)
- [Decorative image](accessible-android/image-decorative.md)
- [Informative image](accessible-android/image.md)
- [Number input field](accessible-android/input-number.md)
- [Password input field](accessible-android/input-password.md)
- [Phone input field](accessible-android/input-phone.md)
- [Text input field](accessible-android/input-text.md)
- [Website input field](accessible-android/input-website.md)
- [Menu](accessible-android/menu.md)
- [Navigation bar](accessible-android/navigation-bar.md)
- [Progress indicator](accessible-android/progress-indicator.md)
- [Radio button](accessible-android/radio.md)
- [Search](accessible-android/search.md)
- [Segmented button](accessible-android/segmented-button.md)
- [Sheet](accessible-android/sheet.md)
- [Slider](accessible-android/slider.md)
- [Snackbar](accessible-android/snackbar.md)
- [Tabs](accessible-android/tabs.md)
- [Time picker](accessible-android/time-picker.md)
- [Toggle switch](accessible-android/toggle-switch.md)
- [Tooltip (rich)](accessible-android/tooltip-rich.md)
- [Tooltip (plain)](accessible-android/tooltip.md)

### Accessible ios

- [Announcement / update](accessible-ios/announcement.md)
- [Button](accessible-ios/button.md)
- [Card box](accessible-ios/card.md)
- [Carousel slideshow](accessible-ios/carousel.md)
- [Checkbox](accessible-ios/checkbox.md)
- [Date picker](accessible-ios/date-picker.md)
- [Alert dialog](accessible-ios/dialog-alert.md)
- [Modal dialog](accessible-ios/dialog-modal.md)
- [Sheet dialog](accessible-ios/dialog-sheet.md)
- [Disclosure expander](accessible-ios/expander.md)
- [Heading](accessible-ios/heading.md)
- [Horizontal scroll](accessible-ios/horizontal-scroll.md)
- [Decorative image](accessible-ios/image-decorative.md)
- [Informative image](accessible-ios/image.md)
- [Number input field](accessible-ios/input-number.md)
- [Phone input field](accessible-ios/input-phone.md)
- [Text input field](accessible-ios/input-text.md)
- [Website input field](accessible-ios/input-website.md)
- [iOS app view](accessible-ios/ios-view.md)
- [Link](accessible-ios/link.md)
- [Picker button](accessible-ios/picker-button.md)
- [Picker wheel / spinner](accessible-ios/picker-wheel.md)
- [Pop-up button](accessible-ios/pop-up-button.md)
- [Popover tooltip](accessible-ios/popover.md)
- [Progress gauge](accessible-ios/progress-gauge.md)
- [Drop/pull down button](accessible-ios/pull-drop-down.md)
- [Radio button](accessible-ios/radio.md)
- [Search input field](accessible-ios/search.md)
- [Segmented control](accessible-ios/segmented-control.md)
- [Slider](accessible-ios/slider.md)
- [Stepper](accessible-ios/stepper.md)
- [Tab bar](accessible-ios/tab-bar.md)
- [Toggle switch](accessible-ios/toggle-switch.md)

> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17

# Introduction to Web Accessibility

## What is accessibility

Make content usable for everyone regardless of abilities.

Web accessibility means people with disabilities can:

- **Use** the web
- **Perceive**,**understand**,**navigate**,and **interact** with the web
- **Contribute** to the web

## Disability statistics

- 15% of world population lives with some form of disability
- In the US, 1 in 5 adults has a disability
- 8% of male have some degree of color blindness

## Wide range of disabilities

(Use image from Inclusive Design at Microsoft)

## Why is accessibility important

- The ADA and Section 508
- People with different abilities should have equal access to the web
- Good accessibility is good user experience

## WCAG

Web Content Accessibility Guidelines

WCAG 2.0 and WCAG 2.1

## Overview of WCAG 2.0

## Level of conformance

- Level A: The minimum level of accessibility
- Level AA: Generally recommended
- Level AAA: Not required as general policy

## What we will cover today

- Focus and tab order
- Color and color contrast
- Text alternatives
- Semantic HTML
- A DIY accessibility test process

## Focus and tab order

- WCAG 2.4.7: Interactive elements should have clear focus.
- WCAG 1.3.2: Navigation (tab) order should be logical and intuitive.
- WCAG 2.1.1: Keyboard users should be able to use functionalities using keyboard only.
- WCAG 2.1.2: Content does not "trap" keyboard focus within subsections.

Demos

## Test focus and tab order

- Tab through page to verify all interactive elements have focus
- Focus order matches intended reading order
- Interact with all links and controls using only keyboard
- No keyboard trap except for modals
- Off-screen/invisible content does not receive focus

## Color and color contrast

- WCAG 1.4.1: Color is not the only visual means of conveying information.
- WCAG 1.4.3: Text needs to have contrast ratio of at least 4.5:1.

Demos

## Test color and color contrast

- Look for content differentiated by color only
- Use a contrast ratio calculator
- Review color contrast issues reported by automated test tool (aXe)

## Text alternatives

WCAG 1.1.1: Non-text content has text alternative.

If image is decorative, use `alt=""`.

Demos

## Write effective alternate text

- Think about how users will be doing with the information
- Be accurate in presenting the content in images
- Be succinct
- No need to use the phrase "image of ..." to describe images

## DIY accessibility test

1. Automated test
2. Keyboard test
3. Screen reader test
4. Color test

## Automated test with aXe

- Tests rendered page in browser
- Less false positives
- Accessible

Demo

## Keyboard test

## Screen reader

## Screen reader basics

## Color test

- Automated color contrast test results may need manual verification
- Look for information differentiated only by color

## Additional resources

- MDN: Accessibility
- Google Developers Web Fundamentals: Accessibility
- The A11Y Project
# 01 HTML, CSS, and Git Refactor

## Description of Project

This project involved taking given HTML and CSS code from a clean repository and modifying them such that the code follows modern semantic tagging structures, is clean and readable, and functions as intended.

> Note: This code is not mine and I claim no rights to it, I simply made modifications to improve accesibility and readibility

## Changes Made:

### Fixes:

- Fixed issue where Search Engine Optimization link in Header would not jump to correct portion of the page

### Changes to HTML:

- Removed div tags for header and footer, replaced with semantic element tags instead
- Replaced all div tags throughout document with section, if classes or ids were present, they were carried over into section tagging
- Applied Prettier formatting to improve readability

### Changes to CSS:

- The .header tag was replaced with header to reflect the new element tagging; this was also done to all subselections under the header class styling
- Replaced multiple instances of duplicate styling being applied to repeating selector groups with a cleaner stacking of selectors before styling

## Project Snapshot

![An image showing a screenshot of my refactored website](./assets/images/my_mockup.png)

> Sorry about the white line, image stitching is not my strong suit, it is not reflected in the actual website
 
## Link to Deployed Site

Access my deployed site here: [My Website!](https://v1brance.github.io/html-css-practice/)

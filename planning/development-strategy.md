# Loruki

A platform for building applications of all types with modern architecture and
scaling.

---

## Setup

- Creating repo from the
  [template](https://github.com/HackYourFutureBelgium/template-html-css)
- Adding collaborators
- Cloning the repo

---

## Home

<!-- NAVBAR -->

### Navigation Bar

This feature developed on a branch `navbar`

#### HTML

- Add `div` tag with class `navbar`, `container-flex`
- Add `h1` tag with class `logo`
- Add `ul` and `li` tags

#### CSS

- Style `navbar` class with `flex` display, `height`, `margin` and `padding`

<!-- SHOWCASE -->

### Showcase

This feature developed on a branch `showcase`

#### HTML

- Add `section` tag with `showcase` class
- Add `div` tag with `container grid` class
- Add `div` tag with `showcase-text` class
- Add `div` tag with `showcase-form card` class
- Add `div` tag with `form-control` class
- Add `input` tag with `btn btn-primary` class
- Add `a` tag with `btn btn-outline` class
- Add `div` tag with `form-control` class

#### CSS

- Style `showcase` with `overflow`, relative as `position`
- Style `showcase-text` and `showcase-form` with animation
- Style `form-control` with margin

<!-- STATS -->

### Stats

This feature was developed on a branch `stats`

#### HTML

- Add `section` tag with `stats` class
- Add `div` tag with `container` class
- Add `p` tag with `text-secondary` class

#### CSS

- Style `stats` with animation
- Style `stats-heading` with max width

<!-- CLI -->

### CLI

This feature was developed on a branch `cli`

#### HTML

- Add `section` tag with `cli` class
- Add `div` tag with `container grid` class
- Add `div` tag with `card` class

#### CSS

- Style `card` with transition

<!-- CLOUD -->

### Cloud

This feature was developed on a branch `cloud`

#### HTML

- Add `div` tag with `container grid` class
- Add `div` with `text-center` class
- Add `h2` tag with `lg` class
- Add `p` tag with `lead my-1` class

<!-- LANGUAGES -->

### Languages

This feature was developed on a branch `languages`

#### HTML

- Add `section` tag with `languages` class
- Add `h2` tag with `md text-center my-2` class
- Add `div` tag with `card` class

#### CSS

- Style `languages` with flex-wrap, transition and add hover

<!-- FOOTER -->

### Footer

This feature was developed on a branch `footer`

#### HTML

- Add `div` tag with `container grid grid-3` class

#### CSS

- Style `grid` with flex-start alignment

## Features

### Navigation Bar

This feature was developed on a branch `navbar-features`.

#### HTML

- Add `div` tag with class `navbar`, `container-flex`
- Add `h1` tag with class `logo`
- Add `ul` and `li` tags

#### CSS

- Style `navbar` class with `flex` display, `height`, `margin` and `padding`

---

### Head

This feature was developed on a branch `head-features`.

#### HTML

- Add a `section` tag with class `features-head bg-primary py-3`.
- Include a `div` container with class `grid` to structure the content.
- Add a heading (`h1`) with class `xl` and a paragraph (`p`) with class `lead`.
- Include an image element (`img`) for the main feature image.

#### CSS

- Style the section with a primary background color and proper spacing.
- Use a grid layout to align the text and image.
- Ensure the image has a responsive width.

---

### Sub-head

This feature was developed on a branch `features-sub-head`.

#### HTML

- Add a `section` tag with class `features-sub-head bg-light py-3`.
- Include a `div` container with class `grid` for layout.
- Add a heading (`h1`) with class `md` and a descriptive paragraph.
- Include an image element (`img`) for additional feature illustration.
- Add a `section` tag with class `features-main my-2`.
- Include a `div` container with class `grid grid-3`.
- Add multiple `div` tags with class `card flex` for individual features:
  - Each card contains an icon (`i`) and a descriptive paragraph (`p`).
  - Use FontAwesome icons for visual representation.

#### CSS

- Style the `features-main` section with proper grid spacing.
- Add hover effects to `card` elements for interactivity.
- Align icons and text within the cards using `flex` display.
- Apply a light background color and consistent padding.
- Use grid layout for alignment between text and image.
- Style the image to ensure responsiveness.

---

### Footer

This feature was developed on a branch `footer-features`.

#### HTML

- Add `div` tag with `container grid grid-3` class

#### CSS

- Style `grid` with flex-start alignment

---

## Docs

### Navigation Bar

This feature was developed on a branch `navbar-docs`.

#### HTML

- Add a `div` tag with class `navbar` and `container-flex`.
- Add an `h1` tag with class `logo` containing a link to `index.html`.
- Add a `nav` element with `ul` and `li` tags for navigation items (`Home`,
  `Features`, `Docs`).

#### CSS

- Style `navbar` with `flex` display for layout alignment.
- Apply a height of `70px`, padding, and background color using the
  `--primary-color` variable.
- Add hover effects for links with a border-bottom.

---

### Head

This feature was developed on a branch `head-docs`.

#### HTML

- Add a `section` tag with class `docs-head bg-primary py-3`.
- Include a `div` container with class `grid` for layout.
- Add a heading (`h1`) with class `xl` and a paragraph (`p`) with class `lead`.
- Include an image element (`img`) with `src="images/docs.png"`.

#### CSS

- Style the section with a primary background color and proper padding.
- Use grid layout to align the text and image.
- Ensure the image has a responsive width.

---

### Docs Main

This feature was developed on a branch `docs-main`.

#### HTML

- Add a `section` tag with class `docs-main my-4`.
- Include a `div` container with class `grid`.
- Add two `div` elements:
  - The first `div` has class `card bg-light p-3`:
    - Include headings (`h3`) for "Essentials" and "Deployment".
    - Add nested `nav` elements with `ul` and `li` tags for links.
  - The second `div` has class `card`:
    - Include content sections with headings (`h2`, `h3`), paragraphs, and
      lists.
    - Add an alert box with class `alert alert-success`.
    - Add a button (`a` tag) with class `btn btn-primary`.
    - Include `pre` and `code` tags for command-line instructions.

#### CSS

- Style the `docs-main` grid for two-column layout on larger screens and
  one-column layout on smaller screens.
- Apply padding and background color to the card with the class `bg-light`.
- Style the alert box with a success theme and include an icon (`i`).
- Add hover effects to links within the navigation.

---

### Footer

This feature was developed on a branch `footer-docs`.

#### HTML

- Add a `footer` tag with class `footer bg-dark py-5`.
- Include a `div` container with class `grid grid-3`.
- Add three sections:
  - Branding: `h1` with the company name and a copyright note.
  - Navigation: `ul` with links to `Home`, `Features`, and `Docs`.
  - Social Media: Links with FontAwesome icons for GitHub, Facebook, Instagram,
    and Twitter.

#### CSS

- Apply a dark background color and consistent padding to the footer.
- Use grid layout to align the three sections horizontally.
- Add hover effects for social media icons, changing their colors.

---

# HTML Advanced – SmileSchool Project

The goal of the following project is to recreate a complete web page layout from a Figma design using HTML only, we will be adding CSS later on.

The project focuses on writing clean, semantic, and accessible HTML code that reflects the structure of the webpage before styling is added.

## Structure Overview

Below is the breakdown of each major section inside the `index.html` file:

### **1. Header**

- Contains the main navigation bar for the page.
  - **Logo** – clickable image linking to the homepage
  - **Navigation links** – “Courses”, “Pricing”, and “Login”

### **2. Banner**

- The introduction section of the site.
  - **Main heading (H1)** – “Get schooled”
  - **Short text line** – “Smiles Grin Laugh”
  - **Button** – “Register for free”
  - **Sub-section** titled “Learn from the pros” containing four profiles:
  - Profile image
  - Name (H3)
  - Small descriptive text or quote

### **3. Quote Section**

- Displays a testimonial or user review.
  - **Image** – person giving the testimonial
  - **Blockquote** – quote text
  - **Author name**
  - **Author role/title**

### **4. Videos Section**

- Lists the most popular tutorials.
  - **Main heading (H1)** – “Most popular tutorials”
  - **Four video cards**, each containing:
  - Thumbnail image
  - Title (H2)
  - Short description text
  - Author block: image + name
  - Rating block: 5 star images
  - Duration text

### **5. Membership Section**

- Highlights free membership benefits.
  - **Main heading (H1)** – “Free membership”
  - **Four feature blocks**, each with:
  - Icon image
  - Title (H2)
  - Short descriptive text
  - **Register button** – “Register for free”

### **6. FAQ Section**

- Frequently Asked Questions area.
  - **Main heading (H1)** – “F.A.Q.”
  - **Two rows**, each containing:
  - Two question/answer blocks
    - Question as (H2)
    - Answer as paragraph text

### **7. Footer**

- Appears at the bottom of the page, outside `<main>`.
  - **Logo image** – repeats the SmileSchool logo
  - **Social media icons** – Facebook, Twitter, Instagram
  - **Text line** – “© SmileSchool 2025”

## Tools Used

Visual Studio Code – for building and testing the HTML structure

Google Chrome – for previewing and checking tag hierarchy

Figma – to inspect design layers and retrieve images

## Details & Notes

As mentioned before, this project only covers the HTML structure.
CSS styling and interactivity will be implemented in future tasks.

Some links and image references are placeholders (#) because the Figma model only included a single page.
No additional pages were created beyond what was shown in the design, this is the reason behind why every navigation link redirects to `index.html`.

Every asset used is stored in the images folder.

Overall the page was built entirely with **semantic elements**, such as:

```html
<header></header>
<main></main>
<section></section>
<nav></nav>
<footer></footer>
<blockquote></blockquote>
```

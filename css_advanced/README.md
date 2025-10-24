# CSS Advanced - SmileSchool Project

This project is built from a Figma design file. It represents the second phase of the SmileSchool project, focusing entirely on translating a design into a clean, maintainable, and modern CSS implementation.

## Project Structure

The primary goal was to take a static, visually-defined Figma file and build a living webpage.

### HTML Structure

The structure implemented was adding a system of classes based on a **`PascalCase` BEM-like (Block-Element-Modifier)** naming system.

- **Block:** The main, standalone component (e.g., `.Banner`, `.Tutorials`, `.Footer`).
- **Element:** A part _inside_ that component, using a dash (`-`) to show it _belongs_ to the block (e.g., `.Banner-title`, `.Tutorials-gallery`, `.Footer-social`).

### CSS Architecture

The CSS was built to be as **DRY (Don't Repeat Yourself)** as possible, in other words, templates were used to simplify the code and to make it clean and concise.

#### CSS Variables (`:root`)

This is the "control panel", per say, for the entire website's design.
All global design (colors, fonts, etc.) were defined as variables.

##### Classes

- .container: This is the main layout tool. Sections are set to 100% width, and this class is used inside them to center the content with a max-width: 1228px and margin: 0 auto.

- .highlight: This class makes text purple and bold (font-weight: 700). It's reused for "Learn," "popular," and "Free."

- .title-normal-weight: This helper class overrides bold text, setting font-weight: 400;. Used it for "from the pros" and "membership."

#### Layout

The CSS exported from Figma uses position: absolute for layout. To add a natural flow CSS Flexbox was implemented.

##### Implementation

- .Header-container: display: flex; + justify-content: space-between; (pushes logo left, nav right).

- .Pros-gallery, .Tutorials-gallery, .Membership-gallery: display: flex; + justify-content: space-between; (arranges the 4 items in a row with even spacing).

- .Quote-container: display: flex; + align-items: center; (to vertically center the image and text).

- .FAQ-grid: display: flex; (to create the two columns).

### Notes

The project is now responsive (to a certain point). By using max-width on the .container instead of a fixed width on the sections, the layout will automatically shrink to fit smaller screens (like tablets and phones).

It is also relevant to mention that the font "Source Sans Pro" family was imported directly from Google's servers.

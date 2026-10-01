# CSS Positioning & Box Model Demo

## Features

- **Global Box Model Reset:** Implements `box-sizing: border-box` across all elements so padding and border widths are included inside element dimensions.
- **Scroll Testing Environment:** Sets `body` height to `2000px` to test vertical scrolling and sticky position triggers.
- **Parent Container (`.lorem`):** A $500 \times 500\text{ px}$ container offset from the left margin with a distinct border.
- **Multi-State Boxes:**
  - `.box`: Base dimensions ($100 \times 100\text{ px}$) with border styling.
  - `.box1`: Solid orange background with a green border.
  - `.box2`: Solid green background with a yellow border.
  - `.box3`: Linear horizontal gradient background (`red` to `yellow`) configured with `position: sticky; top: 0px; left: 200px` to lock into view while scrolling.

---

##  Tech Stack

- **Styling:** CSS3

---

##  Project Structure

```text
├── index.html        # HTML structure referencing the styles
├── style.css         # CSS positioning and box model definitions
└── README.md         # Project documentation

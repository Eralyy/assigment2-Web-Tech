# Assignment 2

Name: Yerali Karkinbayev  
Group: IT-2501  
Course: Web Technologies

## How to open

Open `index.html` in a browser. Keep the `css` and `images` folders next to it. All five tasks are on this page. No installation is needed.

## Part 1: Flexbox

### Task 0: Navigation Bar

![Navigation bar](screenshots/task-0-navigation.png)

The header uses Flexbox, with the logo on the left and links on the right. The links jump to sections using their IDs. `align-items: center` centers the header items vertically, and `gap` separates the links.

### Task 1: Card Row

![Three cards](screenshots/task-1-cards.png)

Three cards contain an image, title, text and button. Flexbox stretches them to equal height in the desktop row. Each card is a flex column, and an automatic top margin puts its form and button at the bottom. A shadow appears on hover.

## Part 2: Grid System

### Task 2: Page Layout with Grid Areas

![Grid layout](screenshots/task-2-grid-layout.png)

This layout example has four named grid areas: header, sidebar, main and footer. The sidebar is on the left, and the main content is on the right. The header and footer span both columns.

### Task 3: Image Gallery

![Nine images with a caption](screenshots/task-3-gallery.png)

The gallery has nine photos in three equal columns with 180px rows and 15px gaps. Captions appear on hover, keyboard focus or when a photo is the link target. They stay visible on devices without hover.

## Part 3: Combining Flexbox and Grid

### Task 4: Portfolio Page

![Portfolio section](screenshots/task-4-portfolio.png)

The portfolio is a section of the same page. It has a Flexbox header, a Grid main area with projects on the left and About Me on the right, and a footer across the bottom. Each project card uses a column Flexbox layout.

## Main files

- `index.html`: navigation and all five tasks.
- `css/style.css`: layout, spacing, hover states and mobile styles.
- `images/`: the nine gallery photos.
- `screenshots/`: screenshots for this report.

## Work summary

The project uses HTML and CSS only. The tasks were arranged as sections, then styled with Flexbox and Grid. The menu uses normal links. The six buttons are submit buttons inside small GET forms whose actions point to section or photo IDs. The browser handles those jumps without JavaScript, and the forms have no data fields.

At 600px and below, the layouts stack into one column. The page was checked at desktop and phone widths, with JavaScript disabled, including menu links, all six buttons and photo captions.

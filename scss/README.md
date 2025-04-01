# **SCSS Folder**

This folder contains all the SCSS files responsible for styling the components and pages of the project. The styles are organized into different folders to enhance scalability, maintainability, and reusability across the project.

## **Folder Structure**

- **base/**: Contains foundational styles for the project such as reset styles, container settings, and base global settings to ensure consistency across all pages and components.
  
- **abstract/**: Holds reusable variables and typography settings that help keep the styles modular and maintainable. It includes design-related settings like colors, font sizes, and global design utilities.

- **components/**: This folder contains SCSS files for individual UI components such as banners, buttons, cards, footers, headers, logos, navbars, rows, and section headers.

- **pages/**: Contains SCSS files for page-specific styles. These styles are designed for individual pages such as the product page.

## **Folder Breakdown**

### **base/**
- **`base.scss`**: Contains the basic, foundational styles like general layout settings, margin/padding resets, and other global styles that set the groundwork for the project.
- **`container.scss`**: Defines the global container styles used across the site to limit the width of content and center it properly.
- **`reset.scss`**: A global reset file that normalizes browser-specific styles and ensures consistent rendering across all browsers by removing default padding, margins, and setting box-sizing to border-box.

### **abstract/**
- **`variables.scss`**: Contains global variables for colors, typography, font sizes, spacing, and other design elements like breakpoints to maintain consistency across the entire project.
- **`typography.scss`**: Defines global typography styles, including font sizes, font families, line heights, and text-related settings for the project.

### **components/**
- **`banner.scss`**: Contains styles for banner components, such as homepage banners, category banners, etc.
- **`buttons.scss`**: Defines the styles for different button types (e.g., primary, outlined, etc.), including padding, background colors, and hover states.
- **`card.scss`**: Contains styles for card components, such as product cards, informational cards, etc., including card layout and styling for images and content.
- **`footercomponents.scss`**: Styles for footer elements, including forms, links, and layout.
- **`header.scss`**: Defines styles for the header, including the background, layout, and text styles for page headers.
- **`logos.scss`**: Styles for logo and small branding elements across the site.
- **`navbar.scss`**: Styles for the navigation bar, including the logo, links, and layout for navigation.
- **`rows.scss`**: Defines grid row styles for creating flexible layouts with rows that adapt to screen size.
- **`sectionheader.scss`**: Contains styles for section headers used to break up content and provide a clear structure within sections of pages.

### **pages/**
- **`product.scss`**: Page-specific styles for the product page, including product details, layout, and styling for product-specific elements like images, price, description, etc.

## **Setup & Installation**

### **1. Install dependencies:**
Make sure you have a SCSS compiler installed (such as `sass` or `node-sass`) in your project.

**To install `sass` via npm:**
```bash
npm install sass

### **2. Compile SCSS to CSS:**
Once your changes are made, you can compile the SCSS into CSS using the following command:

```bash
npm run watch

### **3. Folder Structure Details:**
Each SCSS file is intended to be modular, where:
  - **Base styles** are used globally across the site.
  - **Abstract** holds reusable design settings and helper functions.
  - **Components** contain reusable UI elements and layout components.
  - **Pages** contain styles specific to individual page layouts.

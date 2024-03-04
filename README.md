## CSS Basics

This repository contains a CSS file (`styles.css`) that provides styling for a simple HTML webpage. Below is a brief explanation of some of the key CSS properties used in this file:

### 1. Padding and Margin

- **Padding:** Padding refers to the space between the content and the border of an element. In our CSS file, we've used padding to add space inside elements such as headers, sections, and cards. For example:
  ```css
  .header {
      padding: 20px;
  }
  ```

- **Margin:** Margin refers to the space around an element, outside its border. It creates space between elements. In our CSS file, we've used margin to create space between sections and cards. For example:
  ```css
  .skills {
      margin-top: 20px;
  }
  ```

### 2. Background Color

- **Background Color:** The `background-color` property sets the background color of an element. We've used it to add color to various sections of our webpage. For example:
  ```css
  .introduction {
      background-color: #4caf50; /* Green */
  }
  ```

### 3. Transition

- **Transition:** The `transition` property adds a smooth transition effect to changes in CSS properties. In our CSS file, we've used transitions to make hover effects smoother. For example:
  ```css
  .skill-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
  }
  ```

### 4. Hover Effects

- **Hover Effects:** We've added hover effects to certain elements to enhance user interaction. For example, hovering over a skill card will make it move up and display a shadow effect. This is achieved using the `:hover` pseudo-class. For example:
  ```css
  .skill-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  }
  ```

### Conclusion

Understanding these basic CSS properties and their usage is essential for styling webpages effectively. By manipulating padding, margin, background color, transitions, and hover effects, we can create visually appealing and user-friendly websites.

# css exercices solved

This repository contains my completed solutions for the initial **five CSS exercises** from **The Odin Project's Foundations Curriculum**. This project was designed to solidify my understanding of fundamental CSS concepts, focusing primarily on selectors, grouping, specificity, and element nesting.

---

## 🔑 Key Learnings and Concepts Demonstrated

This project showcases the successful application of the following core CSS and HTML concepts:

### 1. Methods of Adding CSS
Demonstrated all three ways to apply styles, illustrating the CSS **Cascade**'s order of origin (Inline vs. Internal vs. External):
1.  **External:** Linking a separate `style.css` file.
2.  **Internal (Embedded):** Using `<style>` tags in the HTML head.
3.  **Inline:** Using the `style` attribute directly on an element.

### 2. Basic Selectors and Specificity
Practiced using different selector types and understanding how **Specificity** influences style application:
1.  Used **Class selectors** (`.class-name`) for versatile, reusable styling.
2.  Used **ID selectors** (`#id-name`) for unique, high-specificity styling.
3.  Used simple **Element selectors** (`p`, `div`, `button`).

### 3. Grouping and Styling
Applied common styles efficiently:
1.  Used **Grouping Selectors** (e.g., `.btn-a, .btn-b`) to apply uniform styling (font, alignment) to multiple, distinct elements.

### 4. Chaining Selectors
Practiced targeted, high-specificity styling:
1.  Used **Chained Class Selectors** (e.g., `.avatar.proportioned`) to target only elements possessing *all* specified classes.

### 5. Combinators and Nesting
Demonstrated ability to style elements based on their position in the HTML tree:
1.  Used the **Descendant Combinator** (e.g., `.container p`) to target elements that are nested inside a specific parent element, leaving globally matching elements unstyled.

---

## 📏 Margin and Padding Practice

This exercise focuses on applying the **CSS Box Model** properties of **margin** and **padding** to achieve a specific layout and visual spacing.

For this exercise, the `style.css` file was edited to make the divs look like the desired output, strictly by changing the values of `margin` and `padding`. No properties were added, removed, or changed in the HTML.

### Self-Check for Success (Based on Final Code)

The following spacing properties were applied to complete the exercise:

* **Div One** has **34px padding** between its text and border, and a **15px margin** separating it from other elements.
* **Div Three** has **33px padding** between its text and border.
* The gap between **Div Two** and **Div Three** is controlled by **50px margin-bottom** on Div Two.
* **Div Three** is aligned to the right using **`margin-left: auto;`** with a defined width.

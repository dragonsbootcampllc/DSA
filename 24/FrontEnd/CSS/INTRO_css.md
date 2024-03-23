
# CSS INTRODUCTION 📘

## 📝 Topics:   
1. What is CSS?💻
2. Why use CSS?📊
3. How to Add CSS to HTML?🔗
4. CSS Syntax✍️
5. CSS Best Practices🧐
6. What should you focus on while learning CSS?🎯
7. Note📌
8. Resources📚
---

## What is CSS?🤔

- **CSS** stands for **Cascading Style Sheets**.☑️
- It is a style sheet language used for describing the presentation of a document written in HTML.🌐

## Why use CSS?🛠️

- **Separation of Concerns**: CSS allows you to separate the content of a webpage from its presentation.🧩
- **Reusability**: You can define a style once and reuse it across multiple elements.♻️
- **Consistency**: CSS helps in maintaining a consistent look and feel across a website.🎨
- **Flexibility**: You can easily change the layout of a webpage by modifying the CSS.🔄

## How to Add CSS to HTML?🖇️

There are three ways to add CSS to an HTML document:

1. **Inline CSS**: You can add CSS styles directly to an HTML element using the `style` attribute.
   
   ```html
   <h1 style="color: red;">Hello, World!</h1>
   ```

2. **Internal CSS**: You can add CSS styles within the `<style>` element in the `<head>` section of the HTML document.
   
   ```html
    <head>
         <style>
              h1 {
                color: red;
              }
         </style>

    </head>
    ```
3. **External CSS**: You can create a separate CSS file and link it to the HTML document using the `<link>` element.

    ```html
    <head>
          <link rel="stylesheet" type="text/css" href="styles.css">
    </head>
    ```
## CSS Syntax 📝

The basic syntax of a CSS rule consists of a **selector** and a **declaration block**:

```css
selector {
    property: value;
}
```

- **Selector**: It is used to select the HTML element to which the style will be applied.
- **Property**: It defines the style property to be modified.
- **Value**: It specifies the value of the property.

## CSS Best Practices👌


1. **Use External Stylesheets**: Avoid inline styles and internal styles whenever possible.
2. **Organize Your Styles**: Group related styles together to improve readability (groups is better to be as one functionallity).
 - functionallity 
    Example: the hidden class => hide the element.
             the show class => show the element.
             the rounded class => make the element rounded.
> **Note**: The above example is a good practice to explecitly define what you want to do with the element.

3. **Use Comments**: Add comments to your CSS code to explain the purpose of each section. (but don't over comment, just comment the important parts :) )
4. **Use Short and Meaningful Class Names**: Choose class names that are descriptive and easy to understand.

## What should you focus on while learning CSS?
- the most important thing is to understand the placement of the elements in the page.
- the second thing is to understand the properties that you can use to style the elements.
- the third thing is to understand the layout of the page and how to make it responsive.


## Note:🔖

 90% of the time, you will be working with the following properties:
  - **Color**: `color`
  - **Background Color**: `background-color`
  - **Font Size**: `font-size`
  - **Font Family**: `font-family`
  - **Margin**: `margin`
  - **Padding**: `padding`
  - **Border**: `border`
  - **Width**: `width`
  - **Height**: `height`
  - **Display**: `display`
  - **Position**: `position`
  - **Flexbox**: `display: flex`
  - **Grid**: `display: grid`
  - **Box Model**: `margin`, `padding`, `border`
  - **Text Styling**: `font-weight`, `text-align`, `text-decoration`
  - **Pseudo-classes**: `:hover`, `:active`, `:focus`
  - **Media Queries**: `@media`
  - **Animations**: `@keyframes`

 
## 📚 Resources

### General Resources:
    - [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
    - [CSS Tricks](https://css-tricks.com/)
    - [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    - [Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
    - [Learn CSS Layout](http://learnlayout.com/)
---
### Online Courses:
    - [Codecademy](https://www.codecademy.com/learn/learn-css)
    - [freeCodeCamp](https://www.freecodecamp.org/learn/)
    - [Coursera](https://www.coursera.org/courses?query=css)
    - [Udemy](https://www.udemy.com/courses/search/?q=css)
---

### Books:
    - [CSS Secrets](https://www.amazon.com/CSS-Secrets-Lea-Verou/dp/1449372635)
    - [CSS Pocket Reference](https://www.amazon.com/CSS-Pocket-Reference-Visual-Presentation/dp/1492033391)
---

# 🚀 Setup Guide

## 📦 Core Tools
### 1. Install Visual Studio Code
- [Download here](https://code.visualstudio.com/)

### 2. Install Node.js
- [Download here](https://nodejs.org/en/)

### 3. Install Git
- [Download here](https://git-scm.com/)

---

## 🔧 Visual Studio Code Plugins
After installing Visual Studio Code, enhance your development experience with these plugins:
- Live Server 🌐
- Prettier - Code formatter 💅
- Auto Rename Tag 🏷️
- Auto Close Tag 🚪
- HTML CSS Support 🎨
- HTML Snippets ✂️
- CSS Peek 👀
- CSS Modules 💼

---

## 📊 Data in HTML
You can present the following types of data in HTML:
- Text 📝
- Image 🖼️
  - Normal pixelated image (JPG, PNG, GIF, etc.)
  - SVG (Scalable Vector Graphics) - Vector images created by code  
    [**Vector vs. Raster Images** - Choosing the Right Format](https://pavilion.dinfos.edu/Article/Article/2223089/vector-vs-raster-images-choosing-the-right-format/#:~:text=Vector%20graphics%20are%20digital%20art,best%20used%20for%20creating%20photos.)
- Video 📹
- Audio 🎵
- Iframe (external content from other pages or websites) 🌍
- Numbers (displayed as text) 🔢

---

## 📝 HTML5 Elements

### Display Data Elements in HTML5
#### Text Data Elements
- `<h1>` to `<h6>` - Defines HTML headings
- `<p>` - Defines a paragraph
  - `strong`/`bold` - Defines bold text
  - `em`/`italic` - Defines italic text
  - `<mark>` - Defines marked/highlighted text
  - `<del>` - Defines deleted text
  - `<ins>` - Defines inserted text
- `<ul>`/`<ol>` - Defines an unordered/ordered list
  - `<li>` - Defines a list item
- `<table>` - Defines a table
  - `<tr>` - Defines a table row
    - `<th>` - Defines a table header
    - `<td>` - Defines a table cell

##### Text Formatting Data Elements
- `<sub>` - Defines subscripted text
- `<sup>` - Defines superscripted text

##### Quote Data Elements
- `<q>` - Defines a short quotation
- `<blockquote>` - Defines a section quoted from another source

##### Code Data Elements
- `<code>` - Defines a piece of computer code

##### Lines Data Elements
- `<hr>` - Defines a thematic change in the content
- `<br>` - Inserts a single line break

#### Media Data Elements
- `<img>` - Defines an image
- `<video>` - Defines a video
- `<audio>` - Defines an audio
- `<iframe>` - Defines an inline frame

#### Hyperlinks
- `<a>` - Defines a hyperlink

---

### User Interaction Elements in HTML5
- `<form>` - Defines an HTML form for user input
  - `<input>` - Different types for various inputs, like text, password, radio, checkbox, submit, reset, file, hidden, image, button, color, date, date-time, email, month, number, range, search, telephone, time, URL, week, and date-time-local.
  - `<textarea>` - Defines a multiline input control (text area)
  - `<select>` - Defines a drop-down list
    - `<option>` - Defines an option in a drop-down list
    - `<optgroup>` - Defines a group of related options in a drop-down list
- `<canvas>` - Used to draw graphics on the fly via scripting (usually JavaScript)

### Semantic vs. Non-Semantic Coding
> Semantic coding makes your code more readable and understandable both for developers and search engines (SEO), like Google Search.
![EN-Semantic-Search-Non-Semantic](https://github.com/dragonsbootcampllc/DSA/assets/73494683/c4c83df3-24c3-4edc-825a-e6187e176fc8)


---

## 🛠️ Front-End Project Standard Approach
To maintain consistency and organization in front-end projects, follow these guidelines:
1. **Always have three primary files for any task:**
   - `index.html`
   - `index.css`
   - `index.js`
2. **Organize files in a folder named with the date and name of the task:**  
   `YYYY-MM-DD-TaskName`
   - `assets`
     - `Media`
       - `images`
       - `videos`
       - `audios`
     - `fonts`
     - `icons`
   - `src`
     - `index.html`
     - `index.css`
     - `index.js`

3. **Connect the three main files using the following code in the head of the HTML file:**  
    ```html
    <link rel="stylesheet" href="index.css"> <!-- for the CSS file -->
    <script src="index.js"></script> <!-- for the JS file -->
    ```

### HTML Reference
- [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [W3Schools HTML Tag Reference](https://www.w3schools.com/tags/ref_byfunc.asp)

### Structuring HTML Documents
- [W3Schools on HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [SEMRush on Semantic HTML5 Guide](https://www.semrush.com/blog/semantic-html5-guide/)

---

### 📚 Extra Information
#### Hyperlinks - Between pages, within the same page, and external links
```html
<a href="url">Link Text</a>
<a href="#section1">Link Text</a>
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
```

# I Love India Web Page

## 1. Project Title and Description
This project creates a simple HTML web page titled "i love india". The main title is prominently displayed and styled using `highlight.js`, typically a code syntax highlighter, to give it a distinct visual appearance. Below the title, three paragraphs list names of Indian states.

## 2. Setup Instructions
This is a static HTML page and requires no special setup. 

To run it locally:
1.  Save the `index.html` file to your computer.
2.  Open the `index.html` file in your web browser (e.g., Chrome, Firefox, Edge) by double-clicking it.

## 3. Usage Guide
Once opened in a browser, you will see:
*   A large, highlighted title: "i love india".
*   Three paragraphs, each containing the name of an Indian state.

Simply view the page to observe the content and the effect of `highlight.js` on the title.

## 4. Code Explanation
*   **`index.html`**: This is the main and only file for the application.
    *   It includes a `<title>` tag with "i love india" as per requirements.
    *   It links to the `atom-one-dark` theme of `highlight.js` CSS from a CDN to provide a visually distinct style.
    *   Custom CSS is embedded in the `<style>` tags to adjust the appearance of the `h1`, `pre`, and `code` elements, making the `highlight.js` applied title look more like a heading than a code block.
    *   The visible title "i love india" is placed inside an `<h1>` tag, which contains `<pre><code class="language-plaintext">` tags. This structure is essential for `highlight.js` to process and style the text.
    *   Three `<p>` tags follow, each containing an Indian state name: "Maharashtra", "Uttar Pradesh", and "Tamil Nadu".
    *   It includes the `highlight.js` JavaScript library from a CDN at the end of the `<body>`.
    *   A small `<script>` block calls `hljs.highlightAll();` to initialize `highlight.js` and apply its styling to the eligible elements (in this case, the title).

## 5. License Information
This project is licensed under the MIT License. See the LICENSE file (if present) or the license text below for details.

```
MIT License

Copyright (c) [Year] [Your Name/Company Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
### **Lesson 3: iFrames Implementation**

#### **Objective:**

Students will learn how to use an iframe to display a local HTML file (`index.html`) within another HTML document (`iframe.html`) in the same folder.

---

### **Instructions**

#### **Step 1: Create a New HTML File**

1. Inside the `media-gallery` folder, create a new file and name it `iframe.html`.

#### **Step 3: Set Up the Basic HTML Structure in `iframe.html`**

2. Open `iframe.html` in your text editor and add the following basic HTML structure:
   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>iFrame of Index Page</title>
     </head>
     <body></body>
   </html>
   ```

#### **Step 4: Add a Heading**

3. Inside the `<body>` tag, add a heading to indicate what this page is displaying:
   ```html
   <h1>Embedded View of index.html</h1>
   ```

#### **Step 5: Add the iFrame to Display `index.html`**

4. Below the heading, add an `<iframe>` to embed `index.html`:

   ```html
   <iframe
     src="index.html"
     width="800"
     height="600"
     title="Embedded Index Page"
   ></iframe>
   ```

   - **Explanation of attributes**:
     - `src="index.html"`: This tells the iframe to load the `index.html` file located in the same folder as `iframe.html`.
     - `width="800"` and `height="600"`: Adjusts the display size of the iframe.
     - `title="Embedded Index Page"`: Provides an accessible description of the embedded content.

#### **Step 6: Save and Preview**

5. Save `iframe.html` and open it in a web browser.
6. You should see the `index.html` file displayed within the iframe on `iframe.html`.

#### **Step 7: Submit Your Work:**

7. Once you've confirmed that the media gallery looks good, submit the following:
   - The zipped media-gallery folder with the index.html file, iframe.html, and images folder that contains 3 images.
   - Upload it to the classwork assignment on Google Classroom

### **Outcome**

- Students will create an HTML file (`iframe.html`) that embeds their existing `index.html` file using an iframe. This exercise will demonstrate how to embed local files using relative paths in iframes.

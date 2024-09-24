Welcome to the **Tabs project**, which will feature a section containing an image and information. Key components include:

- **Tabs Functionality**:
  - Users can click on different tabs to display specific information related to **Goals**, **History**, and **Vision**.
  
### Project Setup:
1. **HTML Structure**:
   - Create a section with a title and a brief paragraph.
   - Set up a centered layout with two columns, including:
     - An image in the first article.
     - A button container in the second article with three buttons, each having a `data-id` attribute corresponding to the content it reveals.

2. **Content Setup**:
   - Each button controls the visibility of content. Initially, all content sections will have the class `active` to ensure they are displayed.
   - The IDs of the content sections must match the values of the `data-id` attributes from the buttons.

3. **Styling**:
   - Use CSS to style the active button and content, ensuring that only the currently active content is visible.
   - Organize the articles properly within the section for correct CSS application.

4. **JavaScript Functionality**:
   - Add JavaScript to manage the tab functionality, displaying the content associated with the clicked tab and hiding others.

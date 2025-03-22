# Markdown to HTML Converter

![mdtohtml-lightmode](/images/image.png)

This project is a simple web-based Markdown to HTML converter. It allows users to paste Markdown text into a textbox and convert it into HTML. The converted output is displayed in two separate tabs: one for rendered HTML and another for the HTML code with an option to copy the code to the clipboard. Additionally, the site supports a dark/light mode toggle using a modern, stylish toggle switch.

## Features

- **Markdown Conversion:**  
  Uses [Marked.js](https://marked.js.org/) to convert Markdown into HTML dynamically.
  
- **Tabbed Interface:**  
  - **Rendered HTML:** Displays the converted HTML rendered as it would appear in a web page.  
  - **HTML Code:** Shows the raw HTML code with a button to copy it to the clipboard.

- **Dark/Light Mode Toggle:**  
  Easily switch between dark and light themes using a toggle switch located at the top-right of the page.

- **Custom Styled Buttons:**  
  Custom colors applied to the "Convert" and "Copy HTML" buttons provide a distinct and visually appealing interface.

## Getting Started

To use this converter:

1. **Clone or Download:**  
   Download the project files or clone the repository to your local machine.

2. **Open the HTML File:**  
   Open the `index.html` file in your web browser of choice. No additional setup is required as all libraries are referenced via CDN.

3. **Usage:**  
   - Paste your Markdown text into the provided textbox.
   - Click the **Convert** button to see the converted HTML in the rendered output and HTML code tabs.
   - Switch between tabs to view the rendered HTML or the raw HTML code.
   - Use the **Copy HTML** button on the HTML Code tab to copy the code to your clipboard.
   - Use the theme toggle switch at the top-right to switch between Dark Mode and Light Mode.

## Customization

- **Button Styles:**  
  Modify the colors and styles of the buttons by editing the CSS properties in the `<style>` section of the HTML file.

- **Theme Colors:**  
  Change the light and dark mode colors by updating the relevant CSS classes (`.light-mode` and `.dark-mode`).

![mdtohtml-lightmode](/images/mdtohtml-darkmode.JPG)

- **Marked.js Options:**  
  You can customize the behavior of the Marked.js converter by reviewing its documentation and adding configuration options in the JavaScript where the conversion takes place.

## Technologies Used

- **HTML5/CSS3:**  
  Basic structure and styling of the webpage.

- **JavaScript:**  
  For the Markdown conversion, tabbed interface functionality, theme toggling, and clipboard copy functionality.

- **Marked.js:**  
  [Marked.js](https://marked.js.org/) library is used to convert Markdown text into HTML.

## License

This project is open source and available for use under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

- [Marked.js](https://marked.js.org/) for providing a powerful Markdown conversion library.
- Thanks to the open source community for inspiration and support.

---

Feel free to contribute by submitting pull requests or opening issues if you find any bugs or have suggestions for improvements. Enjoy using the Markdown to HTML Converter!
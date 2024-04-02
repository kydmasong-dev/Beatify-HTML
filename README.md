# About Beatify-HTML

<strong>Beautify-HTML</strong> is a tool or software that automatically organizes and <b>formats HTML code to make it more readable and standardized</b>. It helps developers alike to ensure consistent indentation, proper spacing, and overall clean structure within their HTML documents. This can be particularly useful when working with large or complex HTML files, as it makes code maintenance and collaboration easier. BeautifyHTML typically follows specific rules or style guides to format the code according to industry best practices.


HTML Structure:
<!DOCTYPE html>: This declaration specifies that the document is an HTML5 document.
<html lang="en">: The root element of the HTML document. The lang attribute indicates the language (English in this case).
<head>: Contains metadata about the document, such as character encoding, viewport settings, and the page title.
<meta charset="UTF-8">: Specifies the character encoding (UTF-8) for the document.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>HTML Formatter</title>: Defines the title of the webpage.
JavaScript libraries are included using <script> tags.
<style>: Contains CSS rules for styling the HTML content.
<body>: The main content area of the webpage.
CSS Styling:
body: Resets default styles (margin, padding, font, etc.).
.container: Centers content using flexbox. It has a width of 100% and padding.
.large-area: Styles a large text area:
Fixed height of 280px.
Font size of 18px.
Light gray background with white text.
Rounded corners and a border.
.mybtn: Styles a button container:
Centered horizontally.
Flex display for button alignment.
.controls-button: Styles control buttons:
Inline-block display.
Padding, margin, and background color.
White text on a red background.
Cursor changes on hover.
.controls-button:hover: Hover effect for control buttons:
Changes background color to blue.
Responsive Design:
The @media query targets screens with a maximum width of 767px.
For small screens, the .controls-button flex property is set to 1 (equal space for buttons) and margin is adjusted.

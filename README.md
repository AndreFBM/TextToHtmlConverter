# Text to HTML Converter

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Overview

The **Text to HTML Converter** is a web-based tool that allows users to effortlessly convert formatted text into clean HTML code. Utilizing the powerful [CodeMirror](https://codemirror.net/) editor, it offers a user-friendly interface with advanced text editing features, ensuring a seamless conversion experience. Whether you're a developer, content creator, or someone who frequently works with HTML, this tool simplifies the process of generating HTML from plain or formatted text.

## Features

- **Interactive Editor:**
  - Syntax highlighting with CodeMirror.
  - Multiple cursor support for simultaneous editing.
  - Toolbar buttons for quick insertion of formatting characters (e.g., headings, bold, italic, lists).

- **Text Formatting:**
  - Insert and wrap text with Markdown-like syntax (e.g., `#` for H1, `**` for bold).
  - Support for ordered and unordered lists.

- **Undo/Redo Functionality:**
  - Comprehensive undo and redo actions, even after using toolbar buttons.

- **HTML Output:**
  - Generates clean HTML code from formatted text.
  - Easy copy and download options for the HTML output.

- **Live Preview:**
  - Real-time rendering of the generated HTML.
  - Immediate visual feedback of formatting changes.

- **Responsive Design:**
  - Optimized for various screen sizes and devices.



## Usage

### Editor Toolbar

The toolbar provides buttons for inserting common formatting characters:

#### Headings

- **H1:** Inserts `# ` for a level 1 heading.
- **H2:** Inserts `## ` for a level 2 heading.
- **H3:** Inserts `### ` for a level 3 heading.

#### Text Styling

- **Bold (B\*):** Wraps selected text with `**` to make it bold.
- **Italic (I\*):** Wraps selected text with `*` to make it italic.

#### Lists

- **Unordered List (UL):** Inserts `- ` to create a bullet point.
- **Ordered List (OL):** Inserts `1. ` to create a numbered list.

### Multi-Cursor Editing

Leverage CodeMirror's multiple cursor support to edit multiple lines simultaneously:

#### Add Cursors

- Hold `Ctrl` (or `Cmd` on Mac) and click in different areas of the editor to place multiple cursors.

#### Perform Actions

- Use toolbar buttons or type to apply changes across all cursor positions.

### Converting Text to HTML

#### Enter or Paste Text

- Use the editor panel to input your formatted text.

#### Apply Formatting

- Utilize the toolbar buttons or keyboard shortcuts to format your text as desired.

#### Convert to HTML

- Click the **“Convert to HTML”** button to generate the corresponding HTML code.

### Preview and Output

#### HTML Output Panel

- View the generated HTML code in the **HTML Output** panel.
- Use the **“Copy”** button to copy the HTML to your clipboard.
- Use the **“Download”** button to download the HTML code as a `.html` file.
- Use the **“Clear”** button to clear the output panel.

#### Live Preview Panel

- See a real-time rendering of your HTML code in the **Preview** panel, providing immediate visual feedback.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- [**CodeMirror 5**](https://codemirror.net/) - Advanced code editor.

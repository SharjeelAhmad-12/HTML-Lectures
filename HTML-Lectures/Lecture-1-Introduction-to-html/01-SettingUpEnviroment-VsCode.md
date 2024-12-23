# `Setting Up VS Code and Starting an HTML Project`

## Introduction

Visual Studio Code (VS Code) is a popular and powerful code editor for web development. It's lightweight, feature-rich, and works well with multiple programming languages, including HTML, CSS, and JavaScript. This guide will walk you through setting up VS Code, creating a new HTML project, and running it on your local machine.

---

## Step 1: Install Visual Studio Code

To get started with HTML development, you first need to install Visual Studio Code (VS Code).

### How to Install VS Code:

1. Go to the official [VS Code website](https://code.visualstudio.com/).
2. Click on the **Download** button that matches your operating system (Windows, macOS, or Linux).
3. Once the download is complete, open the installer and follow the instructions to complete the installation process.

---

## Step 2: Install Extensions in VS Code

VS Code comes with a rich ecosystem of extensions that can help make web development more efficient. For HTML development, we recommend installing the following extensions:

1. **HTML Snippets**: Provides snippets for faster coding with HTML.
2. **Live Server**: A powerful extension that allows you to open your HTML file in the browser and auto-reload the page whenever you make changes.

### How to Install Extensions:

1. Open VS Code.
2. On the left-hand side, click on the **Extensions** icon (or press `Ctrl+Shift+X`).
3. In the search bar, type the name of the extension you want to install (e.g., "HTML Snippets" or "Live Server").
4. Click on the **Install** button next to the extension.

### Using the Live Server Extension:

The `**Live Server**` extension is a tool that allows you to launch your HTML file in the browser and automatically reload the page whenever you make changes to the code. This is especially useful for web development because it provides a real-time preview of your work.

### How to Use Live Server:

1. After installing the **Live Server** extension, open your HTML file (e.g., `index.html`) in VS Code.
2. Right-click anywhere inside the `index.html` file.
3. From the context menu, select `**Open with Live Server**`.
4. Your default browser will open and display your HTML file. Whenever you make changes to the code in VS Code and save the file, the browser will automatically refresh to show the updated content.

### Example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First HTML Project</title>
</head>
<body>
    <h1>Welcome to My First HTML Project</h1>
    <p>This is a simple HTML page to get started!</p>
</body>
</html>
```
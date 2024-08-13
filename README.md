### Preview


<p align="center">
  <img src="showcase/showcase minimalist.png" alt="urbix" width="1000" height="500">
</p>

---

# VSCode Configuration Setup

## Importing Configuration Files

To import the configuration files into Visual Studio Code, follow these steps:

### JSON Configuration

1. **Locate the directory**: `C:\Users\usuario\AppData\Roaming\Code\User`
2. **Place the JSON configuration file** (`settings.json`) in this directory. This file contains your primary VSCode settings.
3. **Restart Visual Studio Code** to apply the settings.

### CSS Configuration

1. **Locate the directory**: `C:\Users\usuario\AppData\Roaming\Code\User`
2. **Place the CSS configuration file** (`config-vscode.css`) in this directory. This file contains your custom CSS for styling VSCode.
3. **Install and configure the "Custom CSS and JS Loader" extension**:
    - Install the extension from the VSCode Marketplace.
    - Add the following line to your `settings.json` to import the CSS file:
      ```json
      "vscode_custom_css.imports": [
        "file://C:/Users/usuario/AppData/Roaming/Code/User/config-vscode.css"
      ]
      ```
4. **Reload or restart VSCode** to apply the custom CSS.

## Extensions and Brief Descriptions

Here are essential extensions for enhancing your development experience in Visual Studio Code:

- **Auto Rename Tag**: Automatically rename paired HTML/XML tags.
- **Beautify css/sass/scss/less**: Beautify/format CSS, Sass, SCSS, and Less code.
- **Better Comments**: Improve your code commenting with annotations, alerts, queries, and more.
- **CodeSnap**: Quickly generate code snippets from your code.
- **GitHub Copilot**: AI-powered code completion from GitHub.
- **HTML to CSS Autocompletion**: Autocompletion for CSS class names in HTML.
- **Image Preview**: Show image previews in the editor.
- **Path Intellisense**: Autocompletes filenames in your code.
- **Prettier - Code Formatter**: Automatically format your code for consistent style.
- **Subtle Match Brackets**: Enhances bracket matching in subtle ways.

## Deployment for Visualizing Code

To launch your code for visualization, consider using the following extensions:

- **Live Server**: Launch a local development server with live reload feature.
- **Live Preview**: Instantly see live previews of HTML, Markdown, and more.

## Themes

Enhance your Visual Studio Code interface with these themes:

- **Minimal**: A clean and simple theme for a distraction-free coding environment.
- **Minimal Icons**: Icon theme for minimal and clean file and folder visualization.
- **MinimalistDark**: A dark theme with minimalistic design for better focus during late-night coding sessions.
- **GlassIt-VSC**: A transparent theme for a sleek look.
- **Icons**: Icon theme for better file and folder visualization.
- **Ayu**: A simple and elegant theme with bright colors for all day long.

This README provides essential information to set up and enhance your Visual Studio Code environment for efficient coding and development.

---

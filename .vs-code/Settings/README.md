# Visual Studio Code Settings for Web Development

This README provides an overview of the Visual Studio Code settings and extensions that can enhance your web development experience. By configuring these settings and leveraging the power of these extensions, you can streamline your workflow, improve code quality, and boost productivity.

## General Settings

### Workspace Trust Settings

- `security.workspace.trust.untrustedFiles`: `"open"` - Allows opening untrusted files in the workspace, which can be useful when working with web development projects that involve external resources or libraries.

### Editor Associations

- `workbench.editorAssociations`: `{ "*.7z": "default" }` - Associates 7z archive files with the default editor, which can be helpful when working with compressed project files or assets.

### Git Autofetch

- `git.autofetch`: `true` - Automatically fetches changes from the remote repository, keeping your local repository up-to-date with the latest changes from collaborators.

### Live Server Settings

- `liveServer.settings.donotShowInfoMsg`: `true` - Prevents the Live Server extension from showing an informational message on startup.
- `liveServer.settings.CustomBrowser`: `"chrome"` - Sets the default browser to Chrome when using the Live Server extension for previewing web pages locally.

### Icon Theme

- `workbench.iconTheme`: `"material-icon-theme"` - Applies the Material Icon Theme, providing a visually appealing and consistent set of icons for files and folders in the Visual Studio Code interface.

### Cursor Settings

- `editor.cursorStyle`: `"line"` - Sets the cursor style to a full line, making it easier to track the current cursor position in the editor.
- `editor.cursorWidth`: `3` - Increases the cursor width for better visibility.
- `editor.cursorBlinking`: `"expand"` - Sets the cursor blinking animation to expand, making it more noticeable.
- `editor.cursorSmoothCaretAnimation`: `"on"` - Enables smooth cursor animation for a better editing experience.
- `editor.formatOnSave`: `true` - Automatically formats code when saving files, ensuring consistent code formatting throughout the project.
- `editor.formatOnPaste`: `true` - Formats code when pasting, maintaining code style consistency.

### Code Formatting

- `editor.defaultFormatter`: `"esbenp.prettier-vscode"` - Sets the default code formatter to Prettier, a popular code formatting tool that helps maintain consistent code style across your project.
- `"[html]"`: `{ "editor.defaultFormatter": "vscode.html-language-features" }` - Sets the default formatter for HTML files to the built-in HTML language features.
- `"[css]"`: `{ "editor.defaultFormatter": "esbenp.prettier-vscode" }` - Sets the default formatter for CSS files to Prettier.
- `"[javascript]"`: `{ "editor.defaultFormatter": "esbenp.prettier-vscode" }` - Sets the default formatter for JavaScript files to Prettier.

### Spell Checking

- `cSpell.userWords`: `["Guna", "pagelayout", "Palanivel"]` - Adds custom words to the spell checker dictionary, preventing false positives for project-specific terms or names.

### Color Theme

- `workbench.colorTheme`: `"One Dark Pro Darker"` - Applies the "One Dark Pro Darker" color theme to Visual Studio Code, providing a sleek and modern look optimized for comfortable coding.

### CodeGPT Settings

- `CodeGPT.apiKey`: `"CodeGPT Plus"` - Sets the API key for the CodeGPT extension, which provides AI-powered code completion and assistance.
- `CodeGPT.model`: `"CodeGPT Plus"` - Configures the CodeGPT model to be used for code completion and assistance.

### Window Settings

- `window.zoomLevel`: `-1` - Sets the zoom level of the Visual Studio Code window to -1, adjusting the interface size for better visibility or accessibility.

### GitHub Copilot Settings

- `github.copilot.enable`: `{ "*": true, "plaintext": false, "markdown": true, "scminput": false }` - Configures the GitHub Copilot AI assistant to be enabled for all file types except plaintext and source control input, while enabling it for Markdown files.

### Sticky Scroll Settings

- `notebook.stickyScroll.enabled`: `true` - Enables sticky scroll for notebooks, allowing smooth scrolling behavior.
- `editor.stickyScroll.enabled`: `true` - Enables sticky scroll for the editor, providing a consistent scrolling experience.
- `terminal.integrated.stickyScroll.enabled`: `true` - Enables sticky scroll for the integrated terminal, ensuring smooth scrolling when working with console output.
- `editor.largeFileOptimizations`: `false` - Disables large file optimizations, which can be useful when working with large files in web development projects.
- `workbench.editorLargeFileConfirmation`: `1000000000` - Sets the maximum file size for displaying a confirmation prompt when opening large files.
- `liveServer.settings.donotVerifyTags`: `true` - Disables tag verification for the Live Server extension, which can be beneficial when working with non-standard HTML markup or templating languages.
- `typescript.updateImportsOnFileMove.enabled`: `"always"` - Automatically updates import statements when moving TypeScript files, ensuring accurate import paths in your web development projects.
- `editor.fontSize`: `20` - Sets the font size in the editor to 20, adjusting the text size for better readability or accessibility.

## Extension Recommendations

In addition to the settings, the following extensions are included to further enhance the web development experience in Visual Studio Code:

- **Angular Language Service**: Provides intelligent code completion, error checking, and other language services for Angular applications.
- **ESLint**: A popular linting tool that helps identify and fix problems in JavaScript/TypeScript code, improving code quality and maintainability.
- **ES7+ React/Redux/React-Native snippets**: Offers code snippets and integration with Prettier for React, React Native, and Redux development, streamlining the coding process.
- **GitLens**: Enhances the Git experience within Visual Studio Code, providing visual annotations, repository exploration, and powerful comparison tools for better version control management.
- **Auto Rename Tag**: Automatically renames paired HTML/XML tags, helping maintain consistency and reducing errors in web development projects.
- **GitHub Codespaces**: Provides an instant, cloud-based development environment, allowing you to work on your web development projects from anywhere.
- **GitHub Copilot**: An AI pair programmer that can assist with writing code, suggesting completions, and providing explanations, potentially boosting productivity.
- **GitHub Copilot Chat**: Adds AI-powered chat features to GitHub Copilot, enabling better communication and understanding of code in collaborative web development projects.
- **GitHub Theme**: Applies the GitHub theme to Visual Studio Code, providing a consistent look and feel with the GitHub web interface.
- **GitHub Actions**: Enables setting up and managing GitHub Actions workflows directly from Visual Studio Code, useful for automating build, test, and deployment processes for web applications hosted on GitHub.
- **MongoDB for VS Code**: Integrates MongoDB, a popular NoSQL database, into Visual Studio Code, enabling seamless integration with web applications that use MongoDB as the backend database.
- **Docker**: Facilitates creating, managing, and debugging containerized applications, which is essential for deploying web applications in containers.
- **Microsoft Edge Tools for VS Code**: Integrates Microsoft Edge's developer tools into Visual Studio Code, allowing you to inspect and debug your web applications directly from the editor.
- **Live Preview** and **Live Server**: Hosts local development servers for previewing web pages with live reloading, streamlining the development and testing process for web applications.
- **Material Icon Theme**: Applies the Material Design icon theme to Visual Studio Code, enhancing the visual appeal and consistency of the editor.
- **Code Spell Checker**: Helps catch spelling mistakes in your source code, improving code readability and maintainability.

By leveraging these settings you can create a highly productive and efficient web development environment within Visual Studio Code. From code formatting and linting to version control, debugging, and deployment automation, these configurations and tools aim to streamline your workflow and enhance the overall development experience.

Happy coding!

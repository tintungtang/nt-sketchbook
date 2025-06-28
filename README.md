# NT Sketchbook

_Also known as the NashTech Design Ecosystem_

Welcome to NT Sketchbook, a repository designed to empower designers and developers to bring their creative visions to life with ease and efficiency.

## Table of Contents

-   [Overview](#Overview)
-   [Installation](#Installation)
-   [Storybook](#Storybook)
-   [Contributing](#Contributing)
-   [License](#License)

## Overview

NT Sketchbook is an essential toolkit for application development. It provides:

-   A CSS framework delivered with NashTech Design Style Guides as the default theme (`nt-theme`).
-   A library of UI components such as buttons, labels and input controls.
-   A CLI with utilities for application scaffolding and component management.

## Installation

Getting started with NT Sketchbook is simple and straightforward:

1. **Install Node.js**

    Use Node Version Manager (`nvm`) to set up the recommended Node 20 release:

    ```bash
    nvm install 20
    nvm use 20
    nvm alias default 20
    ```

2. **Install pnpm**

    ```bash
    npm install -g pnpm
    pnpm --version
    ```

3. **Install Nx**

    ```bash
    pnpm add -g nx
    nx --version
    ```

4. **Clone the Repository**

    ```bash
    git clone https://github.com/nashtech-garage/nt-sketchbook.git
    cd nt-sketchbook
    ```

5. **Install Essential Dependencies**

    ```bash
    pnpm bootstrap
    ```

## Storybook

1. **Build the stylesheet and Headless UI components**

```bash
pnpm run build:headlessui-storybook
pnpm run build:headlessui-lib
pnpm run build:stylesheet:lib
pnpm run build:stylesheet-preview
```

2. **Run Storybook**

```bash
nx run nt-headless-ui:storybook
```

Then, open your favorite web browser and navigate to `http://localhost:56053/` to immerse yourself in the NT Sketchbook experience.

## Contributing

Join our vibrant community of creators! Your contributions can make a significant impact. Here’s how to get involved:

1. **Fork the Repository.**
2. **Create Your Feature Branch:**
    ```bash
    git checkout -b feature/YourFeature
    ```
3. **Commit Your Changes:**

    ```bash
    git commit -m "Add a compelling new feature"
    ```

4. **Push to the Branch:**
    ```bash
    git push origin feature/YourFeature
    ```
5. **Open a Pull Request.**

## License

This project is proudly licensed under the MIT License. For more details, see the [LICENSE](LICENSE.md) file.

# NT Stylesheet Documentation

This package contains the styling library used across NT Sketchbook. See the [project README](../../README.md) for repository setup instructions.

This directory contains documentation for the **NT Stylesheet** package, which provides the core CSS framework and design tokens for the NT Sketchbook ecosystem.

---

## Overview

**NT Stylesheet** delivers a lightweight, customizable set of CSS utilities and components built for consistency across NT products. It includes:

-   **Design Tokens**: Standardized values for colors, spacing, typography, and more.
-   **Utility Classes**: Ready-to-use classes for layout, spacing, alignment, and responsiveness.
-   **UI Components**: Pre-styled, accessible, and responsive interface elements.
-   **JavaScript Enhancements**: Optional utilities for interactivity (modals, dropdowns, etc.).

---

## Installation

### 1. Install via npm

```bash
npm install @nashtech-garage/nt-stylesheet
```

### 2. Import in your JavaScript or TypeScript entry file

```javascript
import '@nashtech-garage/nt-stylesheet/dist/nt.css'
import '@nashtech-garage/nt-stylesheet/dist/nt.js'
```

### 3. Or include via CDN in your HTML

```html
<link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/@nashtech-garage/nt-stylesheet/dist/nt-stylesheet.css"
/>
<script
    src="https://cdn.jsdelivr.net/npm/@nashtech-garage/nt-stylesheet/dist/nt-stylesheet.js"
    defer
></script>
```

### 4. Use the CSS classes and design tokens in your components

Example:

```html
<button class="nt-btn nt-btn-primary">Submit</button>
```

---

## Components

NT Stylesheet includes a growing list of reusable and composable UI components.

### Component Guides

| Component | Description | Example Class |
| --- | --- | --- |
| [Alert](docs/alert.md) | Displays contextual feedback messages. | `nt-alert` |
| [Avatar](docs/avatar.md) | Shows user profile images with status indicators. | `nt-avatar` |
| [Breadcrumb](docs/breadcrumb.md) | Indicates the user's navigation path. | `nt-breadcrumb` |
| [Button](docs/button.md) | Styled button supporting variants and sizes. | `nt-button` |
| [Card](docs/card.md) | Flexible container for content and actions. | `nt-card-default` |
| [Checkbox](docs/checkbox.md) | Customizable checkbox input. | `nt-checkbox` |
| [Input](docs/input.md) | Stylable text field with validation states. | `nt-input` |
| [Label](docs/label.md) | Consistent styling for form labels. | `nt-label` |
| [Modal](docs/modal.md) | Overlay dialog for user interactions. | `nt-modal` |
| [Multiselect](docs/multiselect.md) | Enhances `<select multiple>` with tag-based selection. | `nt-multi-select-primary` |
| [Popover](docs/popover.md) | Interactive content overlay triggered by click. | `nt-popover` |
| [Progress](docs/progress.md) | Progress bar with color variants. | `nt-progress` |
| [Radio Group](docs/radio-group.md) | Custom radio inputs arranged in grid or row. | `nt-radio` |
| [Switch](docs/switch.md) | Toggle switch built from a checkbox. | `nt-switch` |
| [Table](docs/table.md) | Responsive base styling for tabular data. | `nt-table` |
| [Tooltip](docs/tooltip.md) | Shows contextual hints on hover or focus. | `nt-tooltip` |

Each guide includes component usage, available modifiers, and example markup.

---

## Design Tokens

Tokens are available as CSS variables and Sass variables for design consistency.

### Example CSS Variables

```css
:root {
    --nt-color-primary: #0052cc;
    --nt-spacing-md: 16px;
    --nt-font-size-base: 16px;
}
```

### Utility Example

```html
<div class="bg-primary text-white p-md">
    Welcome to NT Sketchbook!
</div>
```

---

## Customization

You can customize NT Stylesheet in several ways:

-   Override CSS variables using `:root` or component scopes
-   Extend component styles using custom classes
-   Import SCSS files and modify tokens before compilation (Sass users)

For detailed component guides, visit the [documentation folder](docs/README.md).

# SASS/SCSS Project Overview

## Project Objective
This project introduces SASS/SCSS, a CSS preprocessor, to help you write more maintainable and powerful stylesheets. You will learn installation, setup, and core SASS features: variables, nesting, and mixins.

## Learning Objectives
- Install and configure the SASS compiler
- Understand the philosophy and advantages of CSS preprocessors
- Write and compile SASS (.scss) files into CSS
- Use variables, nesting, and mixins in SASS

## Key Concepts
- **Variables:** Store and reuse values (colors, fonts, sizes)
- **Nesting:** Structure CSS rules to mirror HTML
- **Mixins:** Create reusable code blocks

## Installation Steps
1. Install Node.js (v20.16.0 recommended)
2. (Optional) Use nvm to manage Node.js versions
3. Install SASS: `npm install sass -v 3.7.4`
4. Write styles in `.scss` files
5. Compile SCSS to CSS: `npx sass style.scss style.css`

## Example SASS Features
```scss
// Variables
$primary-color: #3498db;
body { color: $primary-color; }

// Nesting
nav {
  ul { margin: 0; }
  li { display: inline-block; }
}

// Mixins
@mixin flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
.container { @include flex-center; }
```

## Real-World Use
SASS is used by companies to manage large codebases, enforce design systems, and speed up development.

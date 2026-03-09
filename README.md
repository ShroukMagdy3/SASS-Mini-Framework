Sass Mini Framework
A lightweight, customizable CSS framework built with Sass, demonstrating advanced Sass features including variables, loops, maps, mixins, extends, and a modular architecture.

📋 Features
12-column Grid System - flexbox-based grid

Utility Classes - Margin, border, and color utilities

UI Components - Cards and buttons with consistent styling

Color System - Configurable color variables and maps

Mixins Library - Reusable mixins for common patterns

Modular Architecture - Organized using Sass partials

🚀 Quick Start
1. Clone or Download
bash
git clone [https://github.com/yourusername/sass-framework.git](https://github.com/ShroukMagdy3/SASS-Mini-Framework.git)

3. Install Sass
bash
# Install globally
npm install -g sass

# OR install locally
npm install sass --save-dev
3. Compile Sass
bash
# One-time compilation
sass sass/main.scss css/style.css

# Watch for changes
sass sass/main.scss:css/style.css --watch
4. Open in Browser
Open index.html in your browser to see the demo.
## 📁 Project Structure

```text
sass-framework/
│
├── sass/
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   │
│   ├── base/
│   │   └── _base.scss
│   │
│   ├── layout/
│   │   └── _grid.scss
│   │
│   ├── components/
│   │   ├── _card.scss
│   │   └── _button.scss
│   │
│   ├── utilities/
│   │   ├── _margins.scss
│   │   └── _borders.scss
│   │
│   └── main.scss
│
├── main.css
├── index.html
└── README.md
```

🎨 Usage Examples

Grid System

html
<div class="row">
  <div class="col-4">Column 4</div>
  <div class="col-4">Column 4</div>
  <div class="col-4">Column 4</div>
</div>
Buttons
html

<button class="btn-primary">Primary Button</button>
<button class="btn-secondary">Secondary Button</button>
<button class="btn-danger">Danger Button</button>
Cards
html

<div class="card">
  <h3 class="card-title">Card Title</h3>
  <p class="card-content">Card content goes here.</p>
  <div class="card-footer">
    <button class="btn-primary">Action</button>
  </div>
</div>
Color Utilities
html

<div class="bg-1">Background Color 1</div>
<p class="text-2">Text Color 2</p>
<div class="bg-3 text-light">Combined</div>
Margin Utilities
html

<div class="m-1">Margin 1 (8px)</div>
<div class="m-2">Margin 2 (16px)</div>
<div class="mt-3">Margin Top 3</div>
<div class="mb-4">Margin Bottom 4</div>
Border Utilities
html

<div class="border">Default Border</div>
<div class="border-primary">Primary Border</div>
<div class="border-secondary">Secondary Border</div>
Circle Helper

html

<div class="circle bg-1" style="width: 100px; height: 100px;">
  Circle
</div>
⚙️ Customization
Variables
Edit sass/abstracts/_variables.scss:

scss
// Colors

$primary-color: #4361ee;
$secondary-color: #7209b7;
$danger-color: #ef233c;

// Spacing

$spacing-unit: 8px;
$total-columns: 12;

// Color Map

$color-map: (
  1: #264653,
  2: #2a9d8f,
  3: #e9c46a,
  4: #f4a261,
  5: #e76f51
);
Mixins

Available mixins in sass/abstract/_mixins.scss:

scss
@include flex-center;           // Center content with flexbox
@include border($color);        // Add border with custom color
@include card-shadow($level);   // Add shadow (level: 1, 2, or 3)

🛠️ Development

Prerequisites
Node.js (for Sass installation)

Sass (Dart Sass)

Available Scripts
bash

# Compile Sass
npm run sass

# Watch for changes
npm run sass:watch
Add to package.json:


📚 Sass Features Demonstrated

✅ Variables - Global configuration

✅ Nesting - Clean, hierarchical code

✅ Partials & @use - Modular architecture

✅ Mixins - Reusable code blocks

✅ Extend - Shared styles

✅ Loops (@for) - Generating grid classes

✅ Maps & @each - Color utilities

✅ Functions - Calculations and logic


Shorok Magdy Shehata - www.linkedin.com/in/shrouk-magdy-shehata-92449824b

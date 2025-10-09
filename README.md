# Clara
!-- Clara CSS Framework --

Clara is a clean, modern, and simple CSS framework built with Sass.  
It provides a customizable design system for developers who want a lightweight and flexible foundation for their web projects.  

Typography & font utilities
    Font families
        .font-karla
        .font-lato
    Font sizes
        .text-xs, .text-sm, .text-md, .text-base, .text-lg, .text-xl, .text-2xl, .text-3xl
    Font weight
        .font-thin, .font-light, .font-normal, .font-bold, .font-black
    Text alignment
        .text-left, .text-center, .text-right, .text-justify
    Text transform
        .uppercase, .lowercase, .capitalize
    Line height
        .leading-tight, .leading-normal, .leading-relaxed
    Decoration
        .underline, .no-underline
    Color utilities
        Text color classes (from $colors):
            .text-primary, .text-secondary, .text-dark, .text-light, .text-white, .text-black
        Background color classes:
            .bg-primary, .bg-secondary, .bg-dark, .bg-light, .bg-white, .bg-transparent
        Border color helpers (pattern):
            .border-name (e.g., .border-primary)

Spacing 
(0, xs, sm, md, lg, xl, 2xl, 3xl)

Margin
    .m-key (all sides)
    .mt-key (top)
    .mr-key (right)
    .mb-key (bottom)
    .ml-key (left)
    .mx-key (horizontal: left & right)
    .my-key (vertical: top & bottom)

Padding patterns:
    .p-key (all sides)
    .pt-key (top)
    .pr-key (right)
    .pb-key (bottom)
    .pl-key (left)
    .px-key (horizontal)
    .py-key (vertical)

Global helpers: 
    .mx-auto, .my-auto

Borders:
    .border
    .border-0, .border-none
    .border-t, .border-r, .border-b, .border-l
    .border-thin, .border-thick
    Radius:
    .rounded-none, .rounded-sm, .rounded, .rounded-md, .rounded-lg, .rounded-xl, .rounded-full

Others
    .text-white, .text-black (explicit)
    .bg-transparent

## Input Components (by Samuel)

### Basic Inputs
All standard HTML input types are styled:
- text, email, password, number, tel, url, search
- date, time, datetime-local, month, week
- textarea, select
- checkbox, radio
- file, range

### Input Sizes
- `.input-sm` - Small input
- Default - Standard size
- `.input-lg` - Large input

### Input Variants
- `.input-primary` - Primary colored border
- `.input-secondary` - Secondary colored background
- `.input-dark` - Dark themed input

### Input States
- `.input-success` - Success state (green)
- `.input-error` - Error state (red)
- `.input-warning` - Warning state (yellow)
- `disabled` - Disabled state

### Input Styles
- `.input-rounded` - Fully rounded borders
- `.input-borderless` - Bottom border only

### Input Groups
- `.form-group` - Wrapper for label + input
- `.input-group` - Container for inputs with icons
- `.has-icon-left` - Icon on left side
- `.has-icon-right` - Icon on right side

### Helper Text
- `.input-help` - Helper text below input
- `.input-success-text` - Success message
- `.input-error-text` - Error message

## List Components (by Samuel)

### Basic Lists
- `ul` - Unordered list
- `ol` - Ordered list
- `dl`, `dt`, `dd` - Description lists

### Styled Lists
- `.list-unstyled` - Remove default styling
- `.list-primary` - Custom arrow bullets (primary color)
- `.list-checkmark` - Checkmark bullets (green)
- `.list-bullet` - Custom bullet points
- `.list-dash` - Dash bullets
- `.list-numbered` - Custom numbered circles

### Layout Lists
- `.list-inline` - Horizontal inline list
- `.list-horizontal` - Horizontal with backgrounds
- `.list-bordered` - Border around entire list
- `.list-striped` - Alternating row colors
- `.list-card` - Card-style list items
- `.list-divided` - Dividers between items

### List Sizes
- `.list-sm` - Small list items
- Default - Standard size
- `.list-lg` - Large list items

### List Spacing
- `.list-compact` - Reduced spacing
- `.list-spaced` - Increased spacing

### List Backgrounds
- `.list-bg-primary` - Primary background color
- `.list-bg-secondary` - Secondary background color
- `.list-bg-dark` - Dark background color

### Description Lists
- `.dl-inline` - Inline description list (grid layout)

### Demo
View the demo file: `demo-inputs-lists.html`

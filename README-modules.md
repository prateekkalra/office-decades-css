# Modular File Structure

## Project Files

### HTML
- `index.html` - Main entry point with complete structure
- `timeline.html` - Original file (backed up as timeline-backup.html)

### CSS Modules (in /styles/)
- `main.css` - Main import file that coordinates all modules
- `base.css` - Base styling, variables, and radio button hiding
- `office-layout.css` - Office container and CSS Grid layout
- `office-zones.css` - Individual zone styling (wall, storage, work, tech, social, personal)
- `timeline.css` - Timeline navigation component
- `decade-themes.css` - Decade-specific background colors and typography
- `decade-content.css` - Decade-responsive zone content changes
- `responsive.css` - Mobile and tablet responsive design

### Dependencies
- `background.css` - Original base styling (imported in base.css)

## Usage

Include the main CSS file in your HTML:
```html
<link rel="stylesheet" href="styles/main.css">
```

## Module Organization

1. **Base Layer**: Foundation styles and variables
2. **Layout Layer**: CSS Grid and positioning
3. **Component Layer**: Individual zone and timeline styling  
4. **Theme Layer**: Decade-specific visual themes
5. **Content Layer**: Dynamic content changes
6. **Responsive Layer**: Mobile/tablet adaptations

All modules use the existing `@layer demo` structure to maintain proper CSS cascade order.
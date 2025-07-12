# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a CSS art competition project called "Office Culture Through the Decades" - an interactive time-lapse visualization showing the evolution of office culture from the 1950s to 2020s using pure CSS, HTML, and SVG animations.

## Project Structure

This is a new project with only a comprehensive plan document (`office-decades-plan.md`) that outlines the complete implementation strategy. The actual code files have not been created yet.

## Development Approach

### Technology Stack
- **Pure CSS, HTML, and SVG only** - No JavaScript required
- **CSS Grid** for layout consistency across decades
- **CSS Custom Properties** for dynamic theming and smooth transitions
- **3D transforms and animations** for morphing effects

### File Organization (To Be Created)
Based on the plan, the project should be organized as:
- `index.html` - Main HTML structure with decade containers
- `styles/` - CSS files organized by decade and component type
- `assets/` - Any SVG graphics or optimized images needed

### Key Technical Requirements
- All animations must run at 60fps
- Total file size should be under 100KB
- Zero JavaScript dependency
- Modern browser compatibility
- Smooth morphing animations between decades using `clip-path`

## Implementation Phases

1. **Structure Phase**: HTML skeleton with timeline navigation and CSS Grid layout
2. **Core Elements Phase**: Animated furniture, characters, and technology items
3. **Polish Phase**: Transition timing, easter eggs, performance optimization
4. **Final Touches Phase**: Browser compatibility, accessibility, intro animation

## Advanced CSS Techniques Used

- **Morphing animations** using `clip-path` with matching point counts
- **Character evolution** using CSS `mask-image` and layered elements
- **Technology progression** with 3D transforms for typewriter-to-computer morphs
- **Environmental details** with animated gradients and particle effects using pseudo-elements
- **Performance optimization** with `will-change`, GPU acceleration, and CSS containment

## Development Commands

Since this is a pure HTML/CSS project with no build system, development can be done with:
- Simple HTTP server for testing (e.g., `python -m http.server` or VS Code Live Server)
- Direct file editing and browser refresh

## Design Principles

- Period-accurate designs for each decade (1950s-2020s)
- Smooth 3-5 second transitions between decades
- Easter eggs and hover effects for interactivity
- Responsive design with different experiences for mobile/tablet/desktop
- Sound-free audio visualization using CSS animations that suggest sounds
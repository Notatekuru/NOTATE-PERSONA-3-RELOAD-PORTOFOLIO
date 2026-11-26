<p align="center">
  <img src="assets/favicon.png" alt="NOTATE-PERSONA-3-RELOAD logo" width="160"/>
</p>

<h1 align="center">NOTATE-PERSONA-3-RELOAD-PORTOFOLIO</h1>

<p align="center">
  An interactive developer portfolio inspired by the visual language of <em>Persona 3 Reload</em>.
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#features">Features</a> •
  <a href="#technology">Technology</a> •
  <a href="#run-locally">Run locally</a> •
  <a href="#controls">Controls</a> •
  <a href="#contributing">Contributing</a>
</p>

---

## Overview

This repository contains a desktop-oriented portfolio experience built around a recreation of the *Persona 3 Reload* pause-menu aesthetic. It presents projects, technical skills, profile information, and contact details through animated menu screens and interactive panels.

The interface is implemented as a static front-end website. It does not require a Node.js package installation or a backend service to preview.

## Features

- **Animated main menu** with angled menu items and a loading screen.
- **Project showcase** with selectable project cards and detail panels.
- **Skills screen** organized into Frontend, Backend, AI & ML, and Languages categories.
- **About screen** with profile information and a short developer introduction.
- **Contact screen** with an email contact link.
- **Visual effects** including video backgrounds, page transitions, custom typography, and interface sound effects.
- **Keyboard interaction** for navigating and controlling the menu.
- **Desktop-first layout** with a notice displayed on smaller screens.

## Technology

The project uses browser-native technologies:

- HTML5 for page structure and content.
- CSS3 for layout, animation, typography, and visual effects.
- Vanilla JavaScript (ES6+) for menu state, navigation, and interactions.
- HTML video and audio elements for background footage and sound effects.

No framework or build tool is required for the current static implementation.

## Run locally

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Start a local static web server:

   ```bash
   python -m http.server 8000
   ```

4. Open [http://localhost:8000](http://localhost:8000) in a desktop browser.

You can also use another static file server or a code editor's live-preview extension. Running through a local server is recommended so that media and other assets load consistently.

## Controls

The interface supports keyboard navigation. Controls are context-sensitive, so the same key can have a different action on different screens.

| Screen | Key | Action |
| --- | --- | --- |
| Main menu | `ArrowUp` / `W` | Move to the previous menu item |
| Main menu | `ArrowDown` / `S` | Move to the next menu item |
| Main menu | `Enter` / `Space` / `B` | Open the selected section |
| Main menu | `F` | Toggle fullscreen |
| Project list | `ArrowUp` / `W` | Select the previous project |
| Project list | `ArrowDown` / `S` | Select the next project |
| Project list | `Enter` / `Space` / `A` | Confirm the selected project |
| Skills | `ArrowLeft` / `Q` | Show the previous skill category |
| Skills | `ArrowRight` / `E` | Show the next skill category |
| Contact | `ArrowUp` / `W` | Select the previous contact row |
| Contact | `ArrowDown` / `S` | Select the next contact row |
| Contact | `Enter` / `Space` | Activate the selected contact row |
| Open subpage | `Esc` / `B` / `Backspace` | Return to the main menu |
| Open modal | `Esc` / `A` | Close the modal |

The on-screen buttons remain available as alternatives to keyboard controls.

## Project structure

The main entry point and key assets are organized as follows:

- `index.html` — page markup and screen structure.
- `css/style.css` — visual styling, responsive rules, and animations.
- `js/main.js` — menu data, screen navigation, and interactive behavior.
- `assets/` — images, icons, and video backgrounds.
- `sfx/` — interface sound effects.
- `fonts/` — local typefaces used by the design.

## Contributing

Suggestions and improvements are welcome. To contribute:

1. Create a branch for your change.
2. Make a focused improvement, such as correcting documentation, improving accessibility, or fixing an interaction.
3. Test the affected screen in a desktop browser.
4. Open a pull request describing what changed and how it was checked.

For collaborative changes, contributors should review the actual diff together and make sure commit attribution reflects the people who genuinely contributed.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/Notatekuru">Notatekuru</a>
</p>

# The MET Landing Page

A responsive landing page for The Metropolitan Museum of Art that presents visitor information, current exhibitions, online resources, and contact details.

## Project Description

The MET Landing Page is a single-page website designed to help visitors explore the museum and plan their visit. It includes museum opening hours, featured exhibitions, online collection resources, contact information, and a feedback form. The layout adapts to mobile, tablet, and desktop screens and provides section-based navigation through an interactive menu.

## Technical Requirements

To run this project locally, you will need:

- **Node.js 18 or newer**
- **npm 9 or newer**
- A modern web browser

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/m-berezovskyy/the-met-landing-page.git
   ```

2. Navigate to the project directory:

   ```bash
   cd the-met-landing-page
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

## Usage

After the development server starts, open the local URL shown in the terminal. Parcel automatically reloads the page when source files change.

To create a production build, run:

```bash
npm run build
```

## Features

- **Responsive layout:** Optimized for mobile, tablet, and desktop screens.
- **Interactive navigation:** A full-screen menu opens from the header and closes after selecting a section.
- **Visitor information:** Displays opening hours and contact details for The Met Fifth Avenue and The Met Cloisters.
- **Exhibition gallery:** Highlights current exhibitions with responsive imagery.
- **Online resources:** Presents collection areas, travel experiences, and virtual group tours.
- **Contact form:** Accepts visitor details and clears submitted fields without reloading the page.
- **Interactive states:** Includes hover, focus, and pressed states for links, images, buttons, and form controls.

## Example

View the live project: [The MET Landing Page](https://m-berezovskyy.github.io/the-met-landing-page/)

## Technologies Used

- **HTML5:** Semantic page structure and content.
- **SCSS:** Responsive layouts, reusable variables, mixins, and component styles.
- **JavaScript (ES6):** Menu interactions and contact form handling.
- **BEM:** Consistent and maintainable CSS class naming.
- **Parcel:** Local development server and production bundling.
- **Node.js and npm:** Dependency and script management.
- **Git and GitHub:** Version control, repository hosting, and deployment.

## Contribution Guidelines

1. Fork the repository.
2. Clone your fork locally.
3. Create a branch for your change.
4. Open a pull request with a clear description of the update.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

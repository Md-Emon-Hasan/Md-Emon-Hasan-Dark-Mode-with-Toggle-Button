![Screenshot 2025-01-15 at 21-48-24 Dark and Light Mode](https://github.com/user-attachments/assets/75d7f1ce-bf17-463e-8e31-8026193d0f35)
# Dark & Light Mode

This is a simple web project that demonstrates a dark and light mode theme toggle functionality. The project is built with HTML, CSS, and JavaScript. It allows users to toggle between a light and dark theme, which is saved in their browser preferences.

## Features
- Light and Dark mode toggle.
- Persistent theme preferences using `localStorage`.
- Smooth transitions for a better user experience.
- Responsive design for different screen sizes (Desktop, Tablet, Mobile).

## Project Structure
The project is divided into three main files:

- `index.html`: The main HTML structure of the page.
- `styles.css`: The stylesheet that includes the styling for light and dark modes.
- `script.js`: The JavaScript file responsible for the theme toggle functionality and saving preferences.

## Installation

1. **Clone or download the repository:**
   You can either clone this repository or download the files directly.

   ```bash
   git clone <repository_url>
   ```

2. **File Structure:**
   After cloning or downloading, the project will have the following structure:
   ```
   /Techy-Dark-Light-Mode
   ├── index.html
   ├── css/styles.css
   ├── js/script.js
   └── README.md
   ```

3. **Run the Project:**
   Open the `index.html` file in any web browser (e.g., Chrome, Firefox, Safari). You should see the page with the light mode enabled by default.

## Usage

- The page will load in **light mode** initially.
- There is a toggle button (a switch) in the top-right corner of the page. 
- Clicking the toggle will switch between **light** and **dark** modes.
- The selected theme is saved in `localStorage`, so when the page is reloaded or revisited, the theme preference is maintained.

### Dark Mode Example
In dark mode, the background color of the page changes to a darker shade, and the text color changes to white, improving readability in low-light environments.

### Light Mode Example
In light mode, the page has a light background and dark text, which is typically more suitable for well-lit environments.

## Technologies Used

- **HTML**: Used to create the structure of the page.
- **CSS**: Used for styling the page and creating responsive designs.
- **JavaScript**: Handles the dark/light mode toggle functionality and stores user preferences.

## Code Explanation

### `index.html`
This file contains the structure of the page, including:
- A header section with the title and the toggle button.
- A main content area with a brief description of the project.
- A footer with the author's information and a link to their LinkedIn profile.

### `styles.css`
This stylesheet:
- Defines the global styles, including background and text colors.
- Uses CSS variables to manage light and dark mode colors.
- Styles the toggle button to make it look like a switch.
- Implements responsive design to make the website look good on mobile devices.

### `script.js`
The JavaScript file:
- Handles the theme toggle functionality. When the toggle button is clicked, it toggles between light and dark modes.
- Saves the selected theme in the browser's `localStorage` so the theme preference persists across page reloads.
- Loads the saved theme preference on page load.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

For any questions or suggestions, feel free to reach out to [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan-695483237/).

---

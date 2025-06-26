# Gemini Workspace Configuration

This file helps Gemini understand the context of the `Destiny Matrix Calculator` project.

## Project Overview

This project consists of two single-file, web-based calculators related to the "Destiny Matrix":

1.  **Destiny Matrix Calculator:** A tool to calculate and display a person's Destiny Matrix chart based on their birth date. All HTML, CSS, and JavaScript are contained within the `Destiny Matrix Calculator.html` file.
2.  **Core Birthday Lister:** A tool to display the "Core number" for a person's birthday over a 9-year cycle. All HTML, CSS, and JavaScript are contained within the `core_birthday_lister.html` file.

The project is self-contained and has no external dependencies.

## Project Structure

-   `Destiny Matrix Calculator.html`: The main application for calculating and displaying the full Destiny Matrix. This file includes all necessary HTML, CSS, and JavaScript.
-   `core_birthday_lister.html`: A supplementary tool to list the "Core number" for a given birth date over many years. This file is also self-contained.
-   `README.md`: The project's README file, which provides an overview and links to live versions.
-   `LICENSE.md`: The license file for the project.
-   `.gitignore`: Standard git ignore file.
-   `.git/`: Git directory.

## Commands

-   **Run Destiny Matrix Calculator:** Open the `Destiny Matrix Calculator.html` file in a web browser.
-   **Run Core Birthday Lister:** Open the `core_birthday_lister.html` file in a web browser.
-   **Test:** There are no automated tests for this project.

## Key Files

-   **`Destiny Matrix Calculator.html`**: This is the primary file for the main application. The core logic for calculating the matrix points is located within the `<script>` tag at the end of this file. The visual representation of the matrix is an embedded SVG within the HTML.
-   **`core_birthday_lister.html`**: This file contains the logic for the second tool. Its JavaScript is also embedded in a `<script>` tag.
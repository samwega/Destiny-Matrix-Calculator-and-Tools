# Gemini Workspace Configuration

This file helps Gemini understand the context of the `Destiny Matrix Calculator & Tools` project.

## Project Overview

This project is a collection of web-based tools for exploring the "Destiny Matrix." It combines the original "Destiny Matrix Calculator" with the "Destiny Matrix Research Tool" into a single repository. The tools are built with self-contained HTML, CSS, and JavaScript files.

The tools included are:
1.  **Destiny Matrix Calculator:** Calculates and displays a person's full Destiny Matrix chart from their birth date.
2.  **Core Birthday Lister:** A supplementary tool that lists the "Core number" for a given birth date over an 81-year cycle.
3.  **Destiny Matrix Research Tool:** Allows for analyzing Destiny Matrix patterns across large date ranges, searching for specific number combinations.

## Project Structure

-   `Destiny Matrix Calculator.html`: The main application for the calculator.
-   `core_birthday_lister.html`: The supplementary Core Birthday Lister tool.
-   `research_tool/`: A directory containing the files for the research tool.
    -   `DestinyMatrixResearchTool.html`: The main file for the research tool.
    -   `Years_List_table.html`: A component or related page for the research tool.
    -   `venv/`: Python virtual environment for the research tool (if applicable).
-   `README.md`: The combined project's README file.
-   `LICENSE.md`: The license file for the project.
-   `.gitignore`: Standard git ignore file.
-   `GEMINI.md`: This configuration file.
-   `.git/`: Git directory.

## Commands

-   **Run Destiny Matrix Calculator:** Open `Destiny Matrix Calculator.html` in a web browser.
-   **Run Core Birthday Lister:** Open `core_birthday_lister.html` in a web browser.
-   **Run Destiny Matrix Research Tool:** Open `research_tool/DestinyMatrixResearchTool.html` in a web browser.
-   **Test:** There are no automated tests for this project.

## Key Files

-   **`Destiny Matrix Calculator.html`**: The primary file for the main calculator application. The core logic is in an embedded `<script>` tag.
-   **`core_birthday_lister.html`**: Contains the logic for the birthday listing tool, also in an embedded `<script>` tag.
-   **`research_tool/DestinyMatrixResearchTool.html`**: The primary file for the research tool. It contains the logic for analyzing date ranges and finding number patterns.

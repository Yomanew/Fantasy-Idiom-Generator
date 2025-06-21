Advanced Fantasy Idiom Generator
Fantasy Idiom Generator Screenshot
A feature-rich, customizable idiom generator for world-builders, writers, and tabletop RPG enthusiasts. This tool creates unique, lore-friendly sayings and proverbs tailored to different fantasy races and themes, helping to add depth and flavor to any fictional setting.

This project is a single, self-contained HTML file that runs entirely in the browser, using localStorage to save user data.

Features
Thematic Generation: Create idioms based on specific races (Dwarves, Elves, Orcs, etc.) and common fantasy themes (War, Nature, Crafting).
Bulk Creation: Generate 1, 3, or 5 idioms at once to quickly populate your world's lore.
Persistent History: Automatically saves a list of the last 20 generated idioms, which persists between sessions.
Favorites System: Save your most-liked idioms to a dedicated favorites list for easy access later.
Copy to Clipboard: Quickly copy an idiom and its meaning with a single click.
Aesthetic Interface: A beautiful, responsive, parchment-and-fantasy-themed UI that looks great on any device.
Highly Extensible: The core generation logic is based on a simple lexicon and template system, making it easy for anyone to add new words, races, themes, or sentence structures.
Zero Dependencies: Runs entirely client-side with no need for a backend server or external libraries (besides Tailwind CSS and Google Fonts loaded from a CDN).
How to Use
Open the index.html file in any modern web browser.
Use the dropdown menus on the left to customize your generation:
Race / Culture: Choose a specific race to add cultural flavor to the idiom, or select "Any" for a general saying.
Theme: Select a theme to focus the idiom's subject matter, or choose "Any" for a random theme.
Quantity: Select how many idioms you want to generate.
Click the "Conjure!" button.
View the results in the main panel. Each generated idiom includes:
The idiom itself.
Its "common tongue" meaning.
Tags for its race and theme.
Buttons to Copy or Favorite the idiom.
Check your History and Favorites in the panels at the bottom. This data is saved in your browser's localStorage, so it will be there when you return!
Technologies Used
HTML5
CSS3
Tailwind CSS
Vanilla JavaScript (ES6+)
Google Fonts
Customization & Extensibility
The generator is designed to be easily expanded. You can add your own content by editing the lexicon and templates objects inside the <script> tag in the index.html file.

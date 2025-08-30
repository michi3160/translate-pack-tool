# Minecraft Translation Resource Pack Generator
A simple and intuitive GUI tool built with Python to automatically translate Minecraft mods, data packs, or language files and generate a ready-to-use resource pack.

## About The Project
This tool was created to simplify the tedious process of translating Minecraft mods and other custom content. Instead of manually translating each line in a language file, you can simply drag and drop a mod's .jar file, a .zip archive, or a folder, and this application will automatically find the English language files (en_us.json), translate the contents, and package everything into a valid Minecraft resource pack.

## Features
- Drag & Drop Interface: Easily drop .jar, .zip, .json files, or entire folders into the application.

- Automatic File Detection: Scans archives and folders to automatically find all en_us.json language files.

- Batch Translation: Translates all text entries quickly using the Google Translate API.

- Searchable Language List: A filterable combo box allows you to quickly find any target language from over 100 options.

- Safe Translation: Automatically skips translating lines with special formatting characters (e.g., %s, %d) to prevent in-game crashes.

- Resource Pack Generation: Creates a correctly structured .zip resource pack, including the pack.mcmeta file, which can be immediately used in Minecraft.

- Real-time Progress: A progress bar and live counters keep you updated on the translation status.

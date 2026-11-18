# Warhammer 40,000 | Beginner's Guide (Final Web Application)

## Project Description
This repository contains the Final Project for the Web Frontend course. It evolves the previous midterm and endterm websites into a complete client-side web application dedicated to the Warhammer 40,000 universe.

## Final Stage Features
The project satisfies all final requirements by extending functionality without breaking previous features:
1. **API Integration (Async/Await & Fetch):** Connects to the public OpenLibrary API on the `lore.html` page to search real Warhammer books, handling loading, success, empty, and error states dynamically.
2. **Object-Oriented Programming (OOP):** Implements `ArmyUnit` and `RosterManager` classes on `tabletop.html` to encapsulate application logic, instantiate multiple objects, and avoid code duplication.
3. **Local Storage Persistence:** The Roster Builder saves user armies as JSON strings in `localStorage`, safely restoring them upon page reload.
4. **Complete CRUD Functionality (Additional Feature 1):** Users can Create, Read, Update, and Delete army units in the Roster Builder on the `tabletop.html` page.
5. **Advanced Search & Sorting (Additional Feature 2):** Users can search specific queries in the Black Library API and sort the retrieved data dynamically by publication year (Newest/Oldest).

## Setup & Testing Instructions
1. Clone this repository or open the provided GitHub Pages link.
2. Open `index.html` in a web browser.
3. Test the **CRUD & OOP** features by navigating to the **Tabletop** page and adding/editing units in the Army Roster Builder.
4. Test the **API & Sorting** features by navigating to the **Lore & Books** page and searching for titles (e.g., "Eisenhorn").

## Live Demo
**Published Website Link:** https://solomondemeter07.github.io/WEB_Final/
**Repository Link:** https://github.com/SolomonDemeter07/WEB_Final
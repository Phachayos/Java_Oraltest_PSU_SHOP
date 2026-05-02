# 🏪 PSU Shop System - Java OOP Documentation

An interactive, web-based documentation project built to showcase a Java Object-Oriented Programming (OOP) system. This UI serves as a comprehensive presentation piece, explaining the core concepts, architecture, and source code of a university merchandise shop system.

## 🚀 Project Overview
I developed this Single Page Application (SPA) using HTML, CSS, and vanilla JavaScript to present my Java OOP coursework (AIC-103). It visually breaks down complex OOP principles into an easy-to-digest format, featuring an interactive code viewer, a custom CSS-built UML class diagram, and a simulated terminal output.

## ✨ Key Features
* **Interactive Navigation:** Smooth, dynamic routing between Overview, OOP Concepts, Source Code, Class Diagram, and Program Output pages without page reloads.
* **Source Code Viewer:** Built-in syntax highlighting simulation for Java files (`Product.java`, `Uniform.java`, `Stationery.java`, `StudentCustomer.java`, `TestMain.java`) complete with a functional "Copy to Clipboard" feature.
* **CSS-Rendered UML:** A fully responsive Class Diagram designed entirely with HTML and CSS, demonstrating the relationships between abstract classes, subclasses, and customer objects without relying on static images.
* **Terminal Simulation:** A mocked console window displaying the compiled execution output for all 5 test cases.

## 🧠 OOP Concepts Demonstrated
The underlying Java project heavily utilizes the 4 pillars of Object-Oriented Programming:
* **Encapsulation:** Protecting data using `private` fields and providing controlled access via getters and setters (e.g., securing the `totalSpent` variable).
* **Inheritance:** Establishing an "IS-A" relationship where the `Uniform` and `Stationery` subclasses extend the base `Product` class.
* **Polymorphism:** Utilizing dynamic method dispatch to call overridden methods (`displayProductInfo()`) on different object types at runtime.
* **Abstraction:** Implementing an `abstract class` for `Product` to enforce a standard structure and method requirement across all item types.

## 🛠️ Tech Stack
* **Frontend UI:** HTML5, CSS3 (Flexbox, Grid, Custom Variables), Vanilla JavaScript.
* **Backend Logic (Documented):** Java (Object-Oriented Programming).

## 🎓 About
This project was developed as part of the AIC-103 curriculum at the College of Computing (CoC), Prince of Songkla University (PSU).

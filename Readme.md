# Random Name Generator  
**Express.js + EJS + Static CSS + Partials + Dynamic Year**  
*Fun, Fast, and Fully Functional Web App*

## **Project Overview**

This is a **lightweight, interactive web application** built with **Node.js**, **Express.js**, and **EJS templating** that generates **hilarious random names** by combining a **random adjective** and a **random noun**.

When the user clicks **"Generate Name"**, the app:
- Picks one adjective from a large predefined list
- Picks one noun from a curated list
- Displays the combo in a big, bold heading (e.g., `Bubbly Unicorn`, `Dazzling Taco`)

Perfect for:
- Learning Express routing
- EJS templating & partials
- Serving static assets
- Dynamic JavaScript in templates

## **Features**

| Feature | Description |
|-------|-----------|
| **Random Name Generation** | Combines 1 adjective + 1 noun |
| **EJS Templating** | Dynamic rendering with `res.render()` |
| **Partials** | Reusable `header.ejs` and `footer.ejs` |
| **Static CSS** | External styling via `public/css/styles.css` |
| **Dynamic Year** | Footer shows current year using JS |
| **Form Handling** | `POST /submit` triggers name generation |
| **Clean UI** | Gradient background, responsive button, modern look |

## **Project Structure**

random-name-generator
 views
*partials
*header.ejs
*footer.ejs
  index.ejs

public
 css
  styles.css
server.js
 package.json
 README.md
.gitignore


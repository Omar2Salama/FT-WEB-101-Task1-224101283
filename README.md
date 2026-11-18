# FT-WEB-101 — Task 1: Profile Page

**Student Name:** Omar Alsayed Alsayed Mohamed Salama  
**Student ID:** 224101283  
**Course:** Field Training I (`FT-WEB-101`) — Fall 2026–2027  
**University:** New Mansoura University, Faculty of Computer Science & Engineering  

## Folder Structure

```text
FT-WEB-101-Task1-224101283/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── me.jpg
└── README.md
```

## Implemented Requirements

- **Heading & Navigation Bar (`header`):** Single `<h1>` with full student name, followed by a Flexbox bar containing the name on the left and section links (`About`, `Skills`, `Contact`) on the right.
- **Profile Section:** Two-column layout featuring a profile photo (`images/me.jpg` with descriptive `alt` text) and a short bio.
- **Cards Row:** Three skill/hobby cards arranged in a row using Flexbox with `gap` and hover styling.
- **Visitor Form:** Includes `Name` and `Email` fields with matching `<label for="...">` and `id` attributes, live greeting text as the visitor types their name, and client-side validation that keeps the form on the page and rejects an empty email.
- **Dark Mode:** Single toggle button (`#dark-btn`) that toggles the `dark` class on `body`; all light and dark colours are defined in CSS using `:root` variables and `body.dark`.
- **Footer:** Single copyright line with a `Back to top` link.

## Built With

- HTML5
- CSS3 (Flexbox & CSS Variables)
- Vanilla JavaScript

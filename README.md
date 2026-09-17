# portfolio
# Rama Portfolio Website

## 1. Project Overview

My project is a personal portfolio designed to showcase my background, technical skills, projects, career goals, and contact information as a Software Engineering graduate.

The website was built using HTML and CSS, with a focus on creating a modern, responsive, and visually engaging interface. It includes multiple sections that allow visitors to learn about my experience, explore my projects, view my technical skills, and contact me.

## 2. Project Objectives

The main objectives of this project are to:

* Create a professional personal portfolio website.
* Present my educational and technical background.
* Showcase projects I have worked on.
* Highlight my programming, database, design, and development skills.
* Provide information about my future career goals.
* Allow visitors to contact me through a contact form.
* Practice and improve my HTML and CSS skills.
* Create a responsive website that works on different screen sizes.
* Implement interactive features using CSS.

---

## 3. Technologies Used

### HTML5

HTML was used to create the structure and content of the website.

### CSS3

CSS was used for the visual design, layout, animations, responsiveness, and theme switching.

Some of the main CSS concepts used are:

* Flexbox
* CSS Grid
* Media Queries
* CSS Animations
* Transitions
* Gradients
* Box Shadows
* Border Radius
* Positioning
* Pseudo-classes such as `:hover`
* CSS variables/state using a checkbox
* Responsive design

### Google Fonts

The website uses the **Poppins** font from Google Fonts to create a clean and modern appearance.

---

## 4. Website Structure

The website is divided into several main sections.

### 4.1 Navigation Bar

The navigation bar appears at the top of the website and provides links to the main sections:

* Home
* About
* Work
* Contact

A theme button is also included, allowing the user to switch between the website's dark and light appearance.

The navigation links use anchor links such as:

```html
<a href="#home">HOME</a>
<a href="#about">ABOUT</a>
<a href="#work">WORK</a>
<a href="#contact">CONTACT</a>
```

This allows visitors to quickly navigate to different sections of the same page.

---

## 5. Hero Section

The Hero section is the first section visitors see when opening the website.

It contains:

* Personal introduction
* Name
* Professional description
* Short description of technical interests
* Contact button

Example:

```html
<h1 class="title">Hi, I'm Rama</h1>
<h2 class="subtitle">Full stack <span>Developer.</span></h2>
```

The hero section also includes a background gradient and a grid overlay to give the page a modern visual appearance.

An entrance animation is applied using CSS:

```css
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

This creates a smooth animation when the content appears.

---

## 6. About Section

The About section provides information about my background, interests, and professional direction.

It includes:

* Educational background
* Technical interests
* Location
* Career availability
* Personal interests

The section also contains several visual skill icons.

### Orbit Animation

One of the main visual elements of the About section is the animated orbit graphic.

The graphic consists of:

* A glowing center
* Two elliptical rings
* Small orbiting dots

CSS animations are used to rotate the orbit rings:

```css
animation: spinOrbit 12s linear infinite;
```

and:

```css
animation: spinOrbitReverse 16s linear infinite;
```

This creates a continuously moving visual effect without using JavaScript.

---

## 7. Skills Section

The Skills section displays my technical abilities in organized cards.

The skills are divided into four categories:

### Programming Languages

* HTML/CSS
* Python
* C++
* JavaScript

### Databases

* Oracle SQL
* MySQL

### Design

* Figma
* UI/UX Design

### Tools & Technologies

* Git
* Agile/Scrum

CSS Grid is used to organize the skill cards:

```css
.skills-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
```

The cards also have hover effects that slightly move the card upward when the user places the cursor over it.

---

## 8. Recent Work Section

The Recent Work section showcases projects that I have worked on.

Each project contains:

* Project name
* Project type
* Project description
* Project image

### Project 1 — UniStudyMate

### Project 2 — Music Website

### Project Layout

## 9. What's Next Section

The What's Next section presents my future career goals and an upcoming project.

### Career Goals

The section describes my goal of continuing to improve both front-end and back-end development skills, with a particular interest in Oracle databases and reliable system design.

### Upcoming Project

The planned project is an:

**Online Instrument Store**

The website will allow users to browse and explore different musical instruments such as:


### Planned Features

The project is planned to include:

1. **Homepage**


2. **Product Listing Page**

3. **Cart and Checkout Page**

4. **Contact and Support Page**

### Planned Technology Stack

* HTML
* CSS
* JavaScript
* Java
* Oracle Database

---

## 10. Contact Section

The Contact section provides visitors with different ways to reach me.

It includes:

* Phone number
* Email address
* Location
* Contact form

The contact form contains:

* Name
* Email
* Message
* Send Message button


## 11. Footer

The footer appears at the bottom of the website.

It contains:

* Portfolio name
* Social media links

The footer is separated from the rest of the page using a horizontal border.

---

## 12. Dark/Light Theme

The website includes a theme-switching feature implemented using **HTML and CSS without JavaScript**.

A checkbox is used to store the theme state:

```html
<input type="checkbox" id="darkmode-theme">
```

A label is connected to the checkbox:

```html
<label for="darkmode-theme" class="darkmode-btn">
```

CSS then detects whether the checkbox is checked:

```css
#darkmode-theme:checked ~ .main {
    background: radial-gradient(...);
}
```

Different colors are applied to the background, text, cards, and form elements when the theme changes.

---

## 13. Responsive Design

The website was designed to work on different screen sizes.

CSS media queries are used to modify the layout for smaller screens.

For example:

```css
@media (max-width: 768px) {
    .title {
        font-size: 42px;
    }

    .subtitle {
        font-size: 26px;
    }
}
```

The project sections also change from multiple columns to a single-column layout on smaller screens.

For example, the skills section changes from two columns to one:

```css
@media (max-width: 850px) {
    .skills-grid {
        grid-template-columns: 1fr;
    }
}
```

The project and contact sections also become vertically stacked on smaller screens.

---

## 14. Animations and Interactive Effects

Several CSS effects were implemented to make the website more interactive.

### Hero Animation

The hero content fades into the page when it loads.

### Hover Effects

Buttons, skill icons, skill cards, project cards, and links have hover effects.

For example:

```css
.btn-contact:hover {
    transform: translateY(-3px);
}
```

### Orbit Animation

The orbit rings continuously rotate around the center graphic.

### Project Image Effect

Project images slightly zoom in when the user hovers over them:

```css
.project-image-wrapper:hover .project-img {
    transform: scale(1.03);
}
```

---

## 15. Future Improvements

Possible improvements for future versions include:

* Add JavaScript functionality to the contact form.
* Connect the contact form to an email service or backend.
* Add real GitHub and LinkedIn links.
* Add more projects.
* Add project GitHub repositories and live demos.
* Add downloadable CV functionality.
* Improve accessibility.
* Add more advanced animations.
* Add a working shopping cart to the Online Instrument Store project.
* Connect future projects to an Oracle database.
* Improve the mobile navigation menu.

---

## 16. Conclusion

The Rama Portfolio Website is a personal project created to present my skills, projects, education, and career goals in a professional and visually engaging way.

The project allowed me to strengthen my understanding of **HTML, CSS, Flexbox, CSS Grid, responsive design, animations, and CSS-based interactions**. It also provides a foundation that can be expanded in the future by adding JavaScript, backend functionality, databases, and additional projects.

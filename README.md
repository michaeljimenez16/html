# The Beatles - Landing Page

A web development project featuring a landing page dedicated to The Beatles. The site includes tour information, a multimedia gallery, and band history, all built with a fully responsive design.

## Features

* **Semantic HTML structure:** Proper use of `header`, `main`, `section`, and `footer` tags for better SEO and accessibility.
* **Hero section:** High-impact visual landing with a clear Call to Action (CTA) for upcoming events.
* **Events section:** Structured HTML table (`thead`, `tbody`) displaying tour dates in cities like Barranquilla, Medellín, and Bogotá.
* **About section:** Descriptive content about the band's history and cultural revolution.
* **Unordered list (ul):** Detailed lists for "Our Influences" and "Social Links."
* **Multimedia gallery:** An image grid implemented with **CSS Grid** for a clean, organized layout.
* **Responsive layout:** Uses **CSS Media Queries** to adapt the design for mobile and desktop views.
* **Navigation:** Functional navigation menu linked to internal page anchors.
* **Clean and organized UI:** Dark theme aesthetic with a focus on readability and modern design.

---

## Responsive Design

The page adapts to different screen sizes:

* **Mobile devices:** Simplified layout and typography adjustments.
* **Desktop screens (>1024px):** Full-width layout optimization.

Media queries are used to adjust:
* Layout (Grid/Flex)
* Typography
* Spacing
* Navigation

---

## How to Run the Project

### Option 1 – Open directly in browser (Recommended)

1. Download or clone the project repository:
   ```bash
   git clone [https://github.com/your-username/project-name.git](https://github.com/your-username/project-name.git)
   

# html
events__table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

.events__table thead {
    background: red;
}

.events__table th, .events__table td {
    padding: 12px;
    border: 1px solid #333;
    text-align: center;
}

/* 5. Multimedia Grid */
.media__grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 10px;
}

.media__grid img {
    width: 100%;
    border-radius: 5px;
}

/* 6. Footer */
.footer {
    background: #000;
    text-align: center;
    padding: 20px;
}

.social {
    display: flex;
    justify-content: center;
    gap: 15px;
    list-style: none;
    margin-top: 10px;
}

/* 7. MEDIA QUERIES (Punto Obligatorio) */
@media (max-width: 768px) {
    /* En móviles el menú se oculta y la sección about se apila */
    .nav__list {
        display: none; 
    }

    .about__content {
        display: block;
        text-align: center;
    }

    .hero h2 {
        font-size: 1.5rem;
    }

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

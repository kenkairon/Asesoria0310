# Asesoria0310
Educativo y de Aprendizaje Personal

---
## Tabla de Contenidos
- [Tecnologías](#Tecnologías)
- [HTML](#HTML)
- [CSS](#CSS)
---
# Tecnologías
- HTML5.
- CSS3. 
--- 
# HTML 
1. HTML  
   ```bash
   <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Asesoria 0310</title>
        <link rel="stylesheet" href="styles.css">
    </head>

    <body>
        <div class="container">
            <nav>
                <img class="logo"
                    src="https://codigofacilito.com/assets/logo-fd9c72981efb94fa3556a7b272d33b45ef8834027fa4fe9959a56e4b2ebaa798.png"
                    alt="logo cf">
                <ul class="menu">
                    <li><a>Contenido</a></li>
                    <li><a>Planes</a></li>
                    <li><a>Contacto</a></li>
                </ul>
            </nav>
            <main>
                <section class="hero">
                    <div class="hero-cta">
                        <h1>El mejor lugar para aprender</h1>
                        <p>+1000 clases y 200 cursos especializados en programación.</p>
                        <button>Crear Cuenta</button>
                    </div>
                    <div class="hero-img">
                        <img src="https://codigofacilito.com/assets/codys/cody_thinking-0c05231ba09a4c632952602216983caaacb9a208a593cba9bc913341236e030a.png"
                            alt="">
                    </div>
                </section>
                <section>
                    <h2>Cursos disponibles</h2>

                    <div class="gallery">
                        <div class="course-card">
                            <img src="https://codigofacilito.com/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBb0lJIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--19192371f26e6924095484a59417d861c19821f9/frontend-premium.jpg"
                                alt="">
                            <h3>Bootcamp Desarrollo Front</h3>
                        </div>
                        <div class="course-card">
                            <img src="https://codigofacilito.com/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBb0lJIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--19192371f26e6924095484a59417d861c19821f9/frontend-premium.jpg"
                                alt="">
                            <h3>Bootcamp Desarrollo Front</h3>
                        </div>
                        <div class="course-card">
                            <img src="https://codigofacilito.com/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBb0lJIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--19192371f26e6924095484a59417d861c19821f9/frontend-premium.jpg"
                                alt="">
                            <h3>Bootcamp Desarrollo Front</h3>
                        </div>
                        <div class="course-card">
                            <img src="https://codigofacilito.com/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBb0lJIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--19192371f26e6924095484a59417d861c19821f9/frontend-premium.jpg"
                                alt="">
                            <h3>Bootcamp Desarrollo Front</h3>
                        </div>
                    </div>


                </section>
            </main>
            <footer>footer</footer>
        </div>

    </body>

    </html>

# CSS
2. CSS
    ```bash 
        :root {
        --light-color: #edf8f2;
        --dark-color: #19192e;
        background-color: var(--light-color);
        color: var(--dark-color);
        font-family: Arial, Helvetica, sans-serif;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    nav .logo {
        height: 30px;

    }

    nav .menu {
        display: flex;
        justify-content: space-between;
        list-style-type: none;
        width: 30%;
        font-weight: bold;
    }

    .hero {
        display: flex;
        padding: 20px;
    }

    .hero-cta {
        width: 50%;
    }

    .hero-cta h1 {
        font-size: 3em;
    }

    button {
        border-radius: 10px;
        background-color: #59ea8a;
        font-weight: bold;
        padding: 10px 20px;
        font-size: 1.1em;
        transition: all 200ms ease-in-out;

    }

    button:hover {
        background-color: #19192e;
        border: 1px solid #59ea8a;
        color: var(--light-color);
        cursor: pointer;
        transition: all 200ms ease-in-out;

    }

    .course-card {
        border-radius: 20px;
        border: 1px solid #ccc;
        overflow: hidden;
    }

    .course-card img {
        width: 100%;
    }

    .gallery {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        gap: 20px;
    }

    .course-card h3 {
        padding: 10px;
    }
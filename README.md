# Asesoria4
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
            <nav><img
                    src="https://codigofacilito.com/assets/logo-fd9c72981efb94fa3556a7b272d33b45ef8834027fa4fe9959a56e4b2ebaa798.png"
                    alt="">
                <ul>
                    <li><a href="#">Contenido</a></li>
                    <li><a href="#">Planes</a></li>
                    <li><a href="#">Contacto</a></li>
                </ul>
            </nav>
            <main>
                <section>hero</section>
                <section>galeria</section>
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

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    aside {
        border: 1px solid red;
    }




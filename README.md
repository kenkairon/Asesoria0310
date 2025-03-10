# Asesoria4
Educativo y de Aprendizaje Personal

---
## Tabla de Contenidos
- [Tecnologías](#Tecnologías)
- [Html](#Html)
- [Css](#Css)
---
# Tecnologías
- HTML5.
- cSS
--- 
# Configuración Inicial 
1. HTML  
   ```bash
   <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Asesoria 0310</title>
    </head>

    <body>
        <nav>nav</nav>
        <main>
            <section>hero</section>
            <section>galeria</section>
        </main>
        <footer>footer</footer>
    </body>

    </html>

2. CSS
    ```bash 
    venv\Scripts\activate

3. Agregamos el requeriments.txt
    ```bash 
    asgiref==3.8.1
    attrs==24.3.0
    Django==5.1.4
    djangorestframework==3.15.2
    drf-spectacular==0.28.0
    inflection==0.5.1
    jsonschema==4.23.0
    jsonschema-specifications==2024.10.1
    psycopg2==2.9.10
    PyYAML==6.0.2
    referencing==0.35.1
    rpds-py==0.22.3
    sqlparse==0.5.3
    tzdata==2024.2
    uritemplate==4.1.1
    
        
4. Actualizamos los pip
    ```bash
    python.exe -m pip install --upgrade pip

5. Instamos las dependencias del archivo requirements.txt
    ```bash
    pip install -r requirements.txt 

6. Crear el proyecto de django crud
    ```bash 
    django-admin startproject crud

7. Ingresamos al crud
    ```bash 
    cd crud


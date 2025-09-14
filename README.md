[estilos.css](https://github.com/user-attachments/files/22324264/estilos.css)
body {
    margin: 0;
    font-family: Verdana, sans-serif;
    background-color: #f4f4f4;
}

/* HEADER */
#header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #222;
    color: white;
    padding: 10px 20px;
}

#logo img {
    height: 60px;
}

#slogan {
    font-size: 18px;
    font-weight: bold;
}

/* CONTENEDOR PRINCIPAL */
#container {
    display: flex;
}

/* MENÚ IZQUIERDO */
#menu {
    width: 200px;
    background: #333;
    padding: 20px;
    min-height: 500px;
}

#menu a {
    display: block;
    color: white;
    text-decoration: none;
    margin-bottom: 15px;
    font-size: 16px;
}

#menu a:hover {
    color: #ffcc00;
}

/* CONTENIDO */
#content {
    flex: 1;
    padding: 20px;
    background: white;
}

#content img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}

/* FOOTER */
#footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}

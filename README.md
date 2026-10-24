# Paleteria-angkl 
     <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paleteria angkl</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="contenedor-menu">
            <table>
                <tr>
                    <td>
                        <img class="imagen-logo" src="https://www.shutterstock.com/image-vector/popsicle-ice-cream-cute-logo-260nw-2202869935.jpg" alt="Logo de la paleteria">
                    </td>
                    <td>
                        <h1 class="titulo-principal">Paleteria angkl"</h1>
                    </td>
                </tr>
            </table>
            
            <nav>
                <a href="index.html">Inicio</a>
                <a href="muestrario.html">Muestrario</a>
                <a href="contacto.html">Contacto</a>
            </nav>
        </div>
    </header>

   
    <main>
        <div class="seccion-bienvenida">
            <h2>Bienvenidos a mi heladeria</h2>
            <p>Disfruta de los mejores helados y paletas hechos 100% con fruta de la mejor calidad sioke</p>
        </div>

        <div class="bloque-sabores">
            <h3>Nuestros Sabores Favoritos</h3>
            <ul>
                <li><strong>Fresa con Crema:</strong> Elaborado con fresas frescas de la region.</li>
                <li><em>Chocolate Suizo:</em> Un toque cremoso e intenso para los amantes del cacao.</li>
                <li><mark>Mango con Chile:</mark> La combinacion perfecta entre dulce y picante.</li>
            </ul>
        </div>

         
        <div class="seccion-tabla">
            <h3>Nuestros Tamaños y Precios</h3>
            <table class="tabla-precios">
                <tr>
                    <th>Tamaño</th>
                    <th>Descripción</th>
                    <th>Precio</th>
                </tr>
                <tr>
                    <td>Chica</td>
                    <td>1 Bola o Paleta sencilla</td>
                    <td>$25.00</td>
                </tr>
                <tr>
                    <td>Mediana</td>
                    <td>2 Bolas combinadas</td>
                    <td>$45.00</td>
                </tr>
                <tr>
                    <td>Grande</td>
                    <td>Especial de la casa (3 sabores)</td>
                    <td>$65.00</td>
                </tr>
            </table>
        </div>

        
        <div class="formulario-contacto">
            <h3>¡Pide tu helado a domicilio!</h3>
            <form>
                <label>Tu Nombre:</label><br>
                <input type="text" placeholder="Escribe tu nombre aquí"><br><br>

                <label>Elige tu sabor principal:</label><br>
                <select>
                    <option>Fresa</option>
                    <option>Chocolate</option>
                    <option>Vainilla</option>
                    <option>Mango</option>
                </select><br><br>

                <label>Comentarios o instrucciones especiales:</label><br>
                <textarea rows="4" cols="30" placeholder="Escribe aquí..."></textarea><br><br>

                <input type="submit" value="Enviar pedido">
            </form>
        </div>
    </main>


    <footer>
        <p class="texto-footer">2026 Paletería Flores Cisneros</p>
    </footer>

</body>
</html>
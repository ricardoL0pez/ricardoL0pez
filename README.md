<style>
        table {
            width: 100%;
            border-collapse: collapse;
        }

        th,
        td {
            padding: 10px;
            border: 1px solid #ccc;
            text-align: center;
        }

        .flip-card {
            perspective: 1000px;
            width: 400px;
            height: 211px;
            position: relative;
        }

        .flip-card-inner {
            width: 100%;
            height: 100%;
            transition: transform 0.6s;
            transform-style: preserve-3d;
            cursor: pointer;
        }

        .flip-card:hover .flip-card-inner {
            transform: rotateY(180deg);
        }

        .flip-card-front,
        .flip-card-back {
            width: 100%;
            height: 100%;
            position: absolute;
            backface-visibility: hidden;
        }

        .flip-card-front {
            background-color: #bbb;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .flip-card-back {
            background-color: #f5f5f5;
            color: black;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            text-align: left;
            transform: rotateY(180deg);
            overflow-y: auto;
            padding: 10px;
            box-sizing: border-box;
            max-height: 100%;/
        }

        .flip-card-back-container {
            margin: 10px;
        }
    </style>

  <h1 align="center">Hi 👋, I'm Ricardo López</h1>
<h3 align="center">Jr. Front-end Web Developer | Senior Graphic Designer
</h3>

<p align="justify">Desarrollador Full Stack y Diseñador Gráfico con más de 10 años de experiencia en la realización de piezas gráficas para medios impresos y digitales.</p>

<p align="justify">He participado en procesos creativos e investigativos, como coordinador de métodos etnográficos, director de arte y diseñador gráfico, comprendiendo la necesidad de la multidisciplinariedad y trabajo en equipo.
</p>
<p align="justify">Mi experiencia como alpinista e instructor de escalada en roca, han desarrollado en mi habilidades como la resolución de problemas, comunicación efectiva, planificación y trabajo en equipo, competencias que tienen una gran relevancia y aplicabilidad en el entorno laboral.
</p>
<br>
<p align="center">
<a href="https://www.linkedin.com/in/josericardolopezsierra/" target="blank"><img align="center" src="./assets/linkedin.svg" alt="https://www.linkedin.com/in/josericardolopezsierra/"  width="40" /></a>
<a href="https://www.behance.net/nitidoart" target="blank"><img align="center" src="https://www.adobe.com/content/dam/shared/images/product-icons/svg/behance.svg" alt="https://www.behance.net/nitidoart"  width="40" /></a>
</p>

<h4>Project</h4>
- 👨‍💻 <a href="https://proyecto-final-front-ashy.vercel.app" target="blank">Care With Love</a>

 <table align="center">
        <tr>
            <td>
                <div class="flip-card">
                    <div class="flip-card-inner">
                        <div class="flip-card-front">
                            <img src="./assets/app-cwl.png" alt="Imagen 1"
                                style="width:100%; height:100%;">
                        </div>
                        <div class="flip-card-back">
                            <div class="flip-card-back-container">
                                <h3 align="center">Pokemon</h3>
                                <p>Single Page Application que facilita la conexión entre cuidadores de adultos mayores
                                    y las familias que buscan este servicio. La plataforma ofrece un proceso de
                                    contratación intuitivo, en donde los cuidadores podrán ofrecer una amplia gama de
                                    servicios personalizados a su experiencia.</p>
                                <p>Tecnologías implementadas</p>
                                <ul>
                                    <li>Lenguajes de Programación: JavaScript</li>
                                    <li>Herramientas de Frameworks: React.js, Express.js</li>
                                    <li>Base de Datos: PostgreSQL</li>
                                    <li>Otras tecnologías: Vite, Node.js,Redux, Axios</li>
                                </ul>
                                <p>PFunciones: Front-end y Back-end developer/p>
                                <p>Proyecto individual</p>
                                <a href="#">Deploy del proyecto</a>
                            </div>
                        </div>
                    </div>
                </div>
            </td>
            <td>
                <div class="flip-card">
                    <div class="flip-card-inner">
                        <div class="flip-card-front">
                            <img src="./assets/app-cwl.png" alt="Imagen 2"
                                style="width:100%; height:100%;">
                        </div>
                        <div class="flip-card-back">
                            <div class="flip-card-back-container">
                                <h3 align="center">Care With love</h3>
                                <p>Single Page Application que facilita la conexión entre cuidadores de adultos mayores
                                    y las familias que buscan este servicio. La plataforma ofrece un proceso de
                                    contratación intuitivo, en donde los cuidadores podrán ofrecer una amplia gama de
                                    servicios personalizados a su experiencia.</p>
                                <p>Tecnologías implementadas</p>
                                <ul>
                                    <li>Lenguajes de Programación: JavaScript</li>
                                    <li>Herramientas de Frameworks: React.js, Express.js</li>
                                    <li>Base de Datos: PostgreSQL</li>
                                    <li>Otras tecnologías: Vite, Node.js, SASS, Redux, Axios</li>
                                </ul>
                                <p>PFunciones: Front-end developer/p>
                                <p>Proyecto realizado con un equipo de 8 Integrantes</p>
                                <a align="center"href="https://proyecto-final-front-ashy.vercel.app/">Deploy del proyecto</a>
                            </div>
                        </div>
                    </div>
                </div>
            </td>
        </tr>
    </table>



<br>
<table align="center">
  <tr>
    <td align="center" width="100">
      <img src="./assets/react.png" width="50" alt="React" />
      <br>React
    </td>
    <td align="center" width="100">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40"  alt="JavaScript" />
      <br>JavaScript
    </td>
    <td align="center" width="100">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="Redux" width="50" />
      <br>Redux
    </td>
    <td align="center" width="100">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="50" />
      <br>HTML5
    </td>
    <td align="center" width="100">
      <img src="./assets/CSS.png" alt="CSS3" width="50" />
      <br>CSS3
    </td>
    <td align="center" width="100">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="SASS" width="50"/>
      <br>SASS
    </td>
    <td align="center" width="100">
      <img src="./assets/js.png" width="50" alt="Nodejs" />
      <br>Nodejs
    </td>
    <td align="center" width="100">
      <img src="./assets/postgresql.svg" width="45" alt="PostgreSQL" />
      <br>PostgreSQL
    </td>
    <td align="center" width="100">
      <img src="./assets/express-w.svg" width="50" alt="ExpressJs" />
    </td>
    <td align="center" width="100">
      <img src="https://www.adobe.com/content/dam/shared/images/product-icons/svg/illustrator.svg" width="40" alt="Illustrator" />
      <br>Illustrator
    </td>
    <td align="center" width="100">
      <img src="https://www.adobe.com/content/dam/shared/images/product-icons/svg/photoshop.svg" width="40" alt="Photoshop" />
      <br>Photoshop
    </td>
    <td align="center" width="100">
      <img src="https://www.adobe.com/content/dam/shared/images/product-icons/svg/indesign.svg" width="40" alt="Photoshop" />
      <br>Indesign
    </td>
    <td align="center" width="100">
      <img src="https://www.adobe.com/content/dam/shared/images/product-icons/svg/premiere.svg" width="40" alt="Photoshop" />
      <br>PremierPro
    </td>
    <td align="center" width="100">
      <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="50" alt="Figma" />
      <br>Figma
    </td>
  </tr>
</table>

<br>

<div align="center"><a href="https://www.buymeacoffee.com/https://www.buymeacoffee.com/josericardq"> <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="https://www.buymeacoffee.com/josericardq" /></a></div>

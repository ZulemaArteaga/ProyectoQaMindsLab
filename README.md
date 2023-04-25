[toc]

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

## INTRODUCCIÓN

El presente proyecto fue creado en respuesta a una solicitud de Blanca Moreno, quien se desempeña como maestra en la plataforma educativa https://www.qamindslab.com/ Este proyecto fue requerido como parte del bootcamp "Testing desde cero".

El éxito de un sitio web de un comercio electrónico no solo depende de una buena plataforma de venta en línea, sino también de una adecuada estrategia de desarrollo y diseño de casos de prueba que permita asegurar su funcionamiento óptimo.

En este proyecto, se analizará el proceso de desarrollo de estrategias y diseño de casos de prueba para Etsy, Inc.

## OBJETIVO

El objetivo principal del proyecto es analizar el sitio web Etsy.com y desarrollar una estrategia de pruebas, además de diseñar casos de prueba necesarios.

***El presente proyecto no contempla realizar las pruebas, solo contempla el análisis y planeación de estrategias y el diseño casos de prueba.***

Con este proyecto, se busca proporcionar una experiencia práctica a los estudiantes del bootcamp, permitiéndonos aplicar los conocimientos teóricos en un entorno de trabajo real.

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

## Etsy

<img src="../../_resources/Etsy_logo.svg" alt="Etsy_logo.svg" width="216" height="108" class="jop-noMdConv">

Etsy es una plataforma de comercio electrónico que se centra en la venta de productos hechos a mano, retro ("vintage") y únicos. Fue fundada en el año 2005 en Brooklyn, Nueva York

La plataforma ofrece productos artesanales y únicos, incluyendo joyas, ropa, accesorios para el hogar y mucho más. Etsy también ofrece herramientas para ayudar a los vendedores a crear y administrar sus tiendas en línea, lo que les permite llegar a una audiencia global y conectarse con compradores interesados en productos hechos a mano y personalizados.

Para el presente proyecto, me enfocaré únicamente en los siguientes tres elementos presentes en la sección de encabezado principal de la página:

- [ ] Barra de búsqueda ("Search bar").
- [ ] Inicio de sesión.
- [ ] Registro de usuario.
- [ ] Carrito de compras.
- [ ] El menú con las categorías:
    -"Home and Favorites"
    -"Jewelry & Accessories"
    -"Clothing & Shoes"
    -"Home & Living"

<img src="../../_resources/Screenshot%202023-04-22%20at%201.42.47%20PM.png" alt="Screenshot 2023-04-22 at 1.42.47 PM.png" width="1249" height="90" class="jop-noMdConv">

*Las categorías "Wedding & Party", "Toys & Entretainment", "Art & Collectibles", "Craft Supplies" y "Gifts & Gift Cards" no son contempladas en el presente proyecto.*

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

## AMBIENTE DE PRUEBA, NAVEGADORES Y SISTEMAS OPERATIVOS

Este análisis está diseñado tomando en cuenta que las pruebas se realizarían en los siguientes ambientes:

- Ambiente de aplicación: Producción
- Navegadores: Chrome,  Firefox y safari.
- Versiones de los navegadores: Ultima versión y la versión inmediatamente anterior.
- Sistema Operativo: Windows 11, Windows 10, Mac OS Ventura y Monterrey.

![Screenshot 2023-04-25 at 11.22.54 AM.png](../../_resources/Screenshot%202023-04-25%20at%2011.22.54%20AM.png)

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

## PAÍS, IDIOMA Y MONEDA DE LA PÁGINA WEB

El presente análisis está diseñado para realizarse en la página web de Estados Unidos de America, en el idioma Inglés y con dólares Estadounidenses.

![Screenshot 2023-04-19 at 5.38.53 PM.png](../../_resources/Screenshot%202023-04-19%20at%205.38.53%20PM.png)

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

## ESTRATEGIAS DE PRUEBA

### Análisis de Prueba Exploratoria

Las pruebas exploratorias nos ayudan a conocer el software en el que vamos a trabajar, con ellas aprenderemos como funciona, lo cual nos ayudará y ampliará el panorama para poder realizar el diseño de las pruebas correspondientes y las estrategias que debemos implementar.

Durante esta prueba exploratoria podremos ponernos en lugar del usuario final, ver como puede pensar, explorar y sentir. Además requerimos un pensamiento crítico lo cual nos ayuda a descubrir una amplia variedad de errores que pudiera tener nuestro software desde una etapa temprana de nuestro proceso de pruebas.

Para el presente análisis primeramente se realizó una prueba exploratoria para conocer el sitio y tomar nota de la primera impresión como usuario.

##### Mapa del sitio web

Adjunto mapa del sitio web:

![Screenshot 2023-04-24 at 11.58.12 AM.png](../../_resources/Screenshot%202023-04-24%20at%2011.58.12%20AM.png)

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

##### Observaciones y sugerencias encontradas durante la prueba exploratoria

**Observaciones**

- El diseño es atractivo y fácil de navegar (a excepción del botón de registro)
- El botón para registro no se encuentra a la vista en la página principal. Para hacer el registro de una cuenta nueva, primero es necesario dar clic en "Sign in"
- Según las políticas de edad para las cuentas de Etsy el dueño de la cuenta debe ser mayor de edad o bien, tener al menos 13 años (cuenta con supervisión del padre o tutor). Sin embargo, al momento de crear una cuenta, la edad no es un requerimiento para el registro de la cuenta. (https://www.etsy.com/legal/minors/)

**Sugerencias**

- Agregar el botón de registro de cuenta, aun lado del botón de inicio de sesión
- Agregar un campo de edad al momento de registrar una cuenta nueva

##### Escenarios de prueba, criterios de alcance y criterios fuera de alcance para las pruebas

Los escenarios a considerar son los siguientes:

![Screenshot 2023-04-25 at 11.49.50 AM.png](../../_resources/Screenshot%202023-04-25%20at%2011.49.50%20AM.png)


##### Riesgos

Los riesgos asociados con este proyecto de análisis son:

- Que se realicen cambios en el sitio.
- El rendimiento del sitio en momentos de sobrecarga de usuarios.

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

##### Tablas de decisiones y matriz de prueba

Para poder diseñar los casos de prueba se realizaron las siguientes tablas de decisiones y la siguiente matriz de prueba:

***Tablas de decisiones para el módulo de Inicio de sesión, Registro de cuenta nueva y Recuperación de contraseña***

![Screenshot 2023-04-25 at 11.28.02 AM.png](../../_resources/Screenshot%202023-04-25%20at%2011.28.02%20AM.png)

***Matriz de prueba para la contraseña***

![Screenshot 2023-04-25 at 11.29.02 AM.png](../../_resources/Screenshot%202023-04-25%20at%2011.29.02%20AM.png)

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

### Análisis de Prueba Visual

Se implementa esta estrategia para evaluar la apariencia visual y el comportamiento de la interfaz de usuario UI

![Screenshot 2023-04-24 at 2.20.15 PM.png](../../_resources/Screenshot%202023-04-24%20at%202.20.15%20PM.png)

Por tal motivo adjunto aquí los bosquejos ("Mockup") de como debe visualizarse cada módulo.

***Barra de búsqueda***

![Screenshot 2023-04-22 at 1.42.47 PM.png](../../_resources/Screenshot%202023-04-22%20at%201.42.47%20PM-1.png)

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

##### Inicio de sesión "Sign in"

<img src="../../_resources/Screenshot%202023-04-22%20at%202.33.11%20PM.png" alt="Screenshot 2023-04-22 at 2.33.11 PM.png" width="350" height="602" class="jop-noMdConv">

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>


##### Registro "Register"

<img src="../../_resources/Screenshot%202023-04-22%20at%202.33.22%20PM.png" alt="Screenshot 2023-04-22 at 2.33.22 PM.png" width="350" height="627" class="jop-noMdConv">

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

##### Carrito de compras con productos listos para compra

<img src="../../_resources/Screenshot%202023-04-22%20at%202.32.20%20PM.png" alt="Screenshot 2023-04-22 at 2.32.20 PM.png" width="568" height="340" class="jop-noMdConv">

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>


### Análisis de Prueba de Usabilidad

Se implementa esta estrategia para analizar la facilidad con la que se puede usar la interfaz así como analizar si dicha interfaz es suficientemente amigable.

- ¿Responde rápida y adecuadamente con la interacción del usuario?
- ¿Se ajusta la orientación de pantalla y zoom?
- ¿Es fácil de navegar en la página?
- ¿Es fácil encontrar lo que se busca (producto, botón de inicio o registro, etc)?


### Análisis de Prueba Funcional

Se implementa esta estrategia para establecer si cada una de las características de los elementos a probar, funcionan según los requerimientos del software.

Para lo cual se especifican los casos de prueba a realizarse por cada escenario:

[Escenarios y Casos de Prueba](https://docs.google.com/spreadsheets/d/1xiVZu4tYAd79q1J7TeGQXYOPXV-mN_6BJBIY55DFF3Y/edit?usp=sharing)

<div style="page-break-after: always; visibility: hidden;">\\pagebreak</div>

## BONUS: PRACTICANDO LA SINTAXIS DE GHERKIN PARA EL ESCENARIO DE REGISTRO DE CUENTA

Como practica adicional, realicé los casos de prueba del escenario dos, que incluye los casos TC01-TC13 utilizando la estructura del lenguaje Gherkin, tal como se muestra acontinuación.

```Gherkin
Característica: Registro de cuenta

    Esquema del escenario: Usuario desea registrar cuenta nueva
        Dado Estoy en la página de Etsy.com
        Y doy clic en "Sign in"
        Y doy clic en "Register"
        Y agrego <"Correo electrónico"> en el campo "Email"
        Y agrego <"Nombre"> en el campo "First Name"
        Y agrego <"Contraseña"> en el campo "Password"
        Cuando doy clic en el boton de "Register" 
        Entonces la nueva cuenta <Se o No Se> registra

    Ejemplos:
        | Email                 | Nombre | Pasword           | Se o No Se |
        | zulema1303@hotmail.com| Zulema | Mycontrasena#12345|    Se      |
        | testingut3st@gmail.com|        | Mycontrasena#12345|    No Se   |
        | testingut3st@gmail.com|        |                   |    No Se   |
        |                       |        | Mycontraseña#12345|    No Se   |
        |                       | Maria  | Mycontrasena#123  |    No Se   |
        |testingut3st@gmail.com | Maria  |                   |    No Se   |
        |                       |        |                   |    No Se   |
        |testingut3st@gmail.com | c# @#$ | Mycontraseña#1239 |    No Se   |
        | testingut3st@gmail.com| s      | sfs               |    No Se   |
        | testingut3st@gmail    | 😜     | 🤪🤓              |    No Se   |
``
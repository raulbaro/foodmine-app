# foodmine

## Descripción

foodmine es una aplicación web desarrollada en Angular que permite a los usuarios pedir comida a domicilio desde sus restaurantes favoritos. La aplicación proporciona una experiencia de usuario fluida y sencilla para explorar menús, realizar pedidos y rastrear el estado de la entrega.

## Características

- **Explorar Restaurantes**: Los usuarios pueden buscar y explorar restaurantes cercanos.
- **Ver Menús**: Cada restaurante tiene su propio menú detallado con descripciones y precios.
- **Realizar Pedidos**: Los usuarios pueden añadir artículos al carrito y realizar pedidos fácilmente.
- **Rastreo de Pedidos**: Seguimiento en tiempo real del estado de los pedidos.
- **Métodos de Pago**: Soporte para múltiples métodos de pago seguros.
- **Historial de Pedidos**: Los usuarios pueden ver y repetir pedidos anteriores.
- **Responsivo**: Diseño adaptable para diferentes tamaños de pantalla y dispositivos.

## Tecnologías Utilizadas

- **Angular**: Framework principal para la construcción de la aplicación.
- **TypeScript**: Lenguaje de programación utilizado en Angular.
- **Angular CLI**: Herramienta de línea de comandos para gestionar el proyecto.
- **HTML5 & CSS3**: Estructura y estilo de la aplicación.
- **Bootstrap**: Framework de CSS para el diseño responsivo.
- **Firebase**: (opcional) Utilizado para la autenticación de usuarios y base de datos en tiempo real.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

- Node.js y npm (Node Package Manager)
- Angular CLI

## Instalación

Sigue estos pasos para instalar y ejecutar el proyecto en tu máquina local:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/raulbaro/foodmine-app.git
2. Navega al directorio del proyecto:
   ```bash
   cd foodmine
3. Instala las dependencias del proyecto:
   ```bash
   npm install
4. Configura las variables de entorno si es necesario (por ejemplo, credenciales de Firebase):

    - Crea un archivo src/environments/environment.ts y src/environments/environment.prod.ts.
    - Añade tus configuraciones específicas al archivo de entorno.
5. Inicia el servidor de desarrollo:
   ```bash
   ng serve
6. Abre tu navegador y visita http://localhost:4200 para ver la aplicación en funcionamiento.
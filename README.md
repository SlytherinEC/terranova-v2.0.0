# Terranova v2.0.0

Terranova es un proyecto desarrollado con React que lleva la experiencia de un juego de mesa tipo *dungeon crawler* al mundo web. El jugador asume el papel de un capitán que debe guiar a su tripulación a través de un mapa lleno de desafíos para recuperar los códigos necesarios y escapar antes de que los alienígenas los derroten.

---

## Tabla de Contenidos

- [Características](#características)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Scripts Disponibles](#scripts-disponibles)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Características

- Juego interactivo con mapas hexagonales.
- Sistema de exploración y combate.
- Narrativa inmersiva que incluye desafíos y decisiones estratégicas.
- Basado en React 19, con un enfoque en el rendimiento y la modularidad.

---

## Requisitos Previos

Asegúrate de tener instalado lo siguiente:

- **Node.js** (versión 14 o superior recomendada): [Descargar aquí](https://nodejs.org/)
- **npm** (incluido con Node.js) o **Yarn** (opcional): [Descargar aquí](https://yarnpkg.com/)

---

## Instalación

Sigue estos pasos para configurar y ejecutar el proyecto:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/SlytherinEC/terranova-v2.0.0.git
   cd terranova-v2.0.0

2. **Instalar las dependencias:**
   ```bash
   npm install

3. **Iniciar el servidor de desarrollo:**
    ```bash
    npm start

4. **Abrir la aplicación en tu navegador:**
La aplicación estará disponible en: http://localhost:3000

---

## Estructura del Proyecto
    
    terranova-v2.0.0/
    ├── public/               # Archivos públicos (index.html, favicon, etc.)
    ├── src/                  # Código fuente de la aplicación
    │   ├── components/       # Componentes React
    │   ├── styles/           # Archivos CSS
    │   ├── App.js            # Componente principal
    │   └── index.js          # Punto de entrada de la aplicación
    ├── package.json          # Configuración del proyecto
    └── README.md             # Documentación del proyecto

---

## Scripts Disponibles

En el directorio del proyecto, puedes ejecutar los siguientes comandos:

- Iniciar el servidor de desarrollo:

    ```bash
    npm start

Inicia el servidor de desarrollo. Abre http://localhost:3000 en tu navegador para ver la aplicación en vivo.

- Construye la aplicación para producción. Los archivos se generarán en la carpeta build.
    ```bash
    npm run build


- Ejecuta las pruebas unitarias definidas en el proyecto.
    ```bash
    npm test

- Exponer la configuración de React (irreversible):
    ```bash
    npm run eject

- Nota: Este comando solo debe usarse si necesitas personalizar la configuración de Webpack, Babel u otros ajustes avanzados.

---

## Tecnologías Utilizadas

- React 19: Biblioteca para construir interfaces de usuario. [Documentación oficial](https://reactjs.org/)
- React Scripts: Herramientas y configuración para proyectos React.
- Web Vitals: Para medir el rendimiento y la experiencia del usuario.

---

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas colaborar, sigue estos pasos:

1. Haz un fork del repositorio.
    ```bash
    git fork https://github.com/SlytherinEC/terranova-v2.0.0.git

2. Crea una nueva rama para tu funcionalidad:

    ```bash
    git checkout -b feature/nueva-funcionalidad
    
3. Realiza los cambios y confirma los commits:

    ```bash
    git commit -m 'Descripción de la funcionalidad'

4. Envía los cambios a tu repositorio fork:

    ```bash
    git push origin feature/nueva-funcionalidad

5. Crea un Pull Request desde tu repositorio en GitHub.

¡Nos encantaría recibir tus aportes!

---

## Licencia
Este proyecto está bajo la licencia MIT. Puedes usar, modificar y distribuir el código bajo los términos de esta licencia.



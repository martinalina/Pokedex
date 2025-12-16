# Pokedex SPA - Framework7 v3 Challenge 📱

Este proyecto es una **Single Page Application (SPA)** desarrollada como parte del proceso de inducción técnica para el desarrollo sobre plataformas Microsoft/SharePoint.

El objetivo es demostrar el dominio de **Framework7 (Core v3)**, la manipulación del DOM, el consumo de APIs RESTful y el renderizado eficiente de datos mediante **Listas Virtuales**.

## 🚀 Funcionalidades

La aplicación utiliza un diseño **Split View** (Vista Dividida) que integra tres módulos funcionales consumiendo la [PokeAPI](https://pokeapi.co/):

1.  **Selector de Generaciones:**
    * Carga masiva de datos controlada.
    * Renderizado optimizado mediante `Virtual List` de F7.
    * Navegación por las distintas regiones (Kanto, Johto, Hoenn, etc.).

2.  **Filtro por Tipos (Simulación de Negocio):**
    * Consulta a endpoint de categorías (`/type`).
    * Filtrado dinámico de elementos y recarga de listas.

3.  **Shiny Hunter (Buscador Visual):**
    * Búsqueda por ID o Nombre.
    * Manipulación dinámica de atributos (src) para alternar entre versiones "Normal" y "Shiny" en tiempo real.

## 🛠 Stack Tecnológico

* **Framework:** Framework7 v3 (Core/Vanilla JS).
* **API:** PokeAPI (REST).
* **Lenguajes:** HTML5, CSS3, JavaScript (ES6).
* **Arquitectura:** SPA con Router de F7.

## 📦 Instalación y Despliegue

### Requisitos
* Cualquier servidor web local (Live Server, http-server, Apache, etc.).

### Pasos para ejecutar
1.  Clonar el repositorio:
    ```bash
    git clone [https://github.com/martinalina/Pokedex.git](https://github.com/martinalina/Pokedex.git)
    ```
2.  Navegar a la carpeta del proyecto.
3.  Iniciar un servidor local.
    * **Opción A (VS Code):** Instalar la extensión "Live Server", abrir `index.html` y dar click en "Go Live".
    * **Opción B (Node.js):**
        ```bash
        npx http-server .
        ```
4.  Abrir el navegador en `http://127.0.0.1:8080` (o el puerto indicado).

---
*Desarrollado por Martina, diciembre 2025*

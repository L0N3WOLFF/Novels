# Novelas

Este repositorio contiene una colección de novelas, organizadas para facilitar el acceso y la lectura. Cada novela se almacena en su propia carpeta, lo que permite una navegación sencilla a través del contenido.

## Índice

- [Novelas disponibles](#novelas-disponibles)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Cómo Usar](#cómo-usar)

## Novelas disponibles

Actualmente, el proyecto incluye las siguientes novelas:

- **Against The Gods (ATG)**
- **Destined to be Loved by Villains (DLBV)**
- **Emperors Domination (ED)**
- **Martial God Asura (MGA)**
- **The Steward Demonic Emperor (SDE)**

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

.
├── content/
│ ├── Against The Gods/
│ │ └── ATG-Update.txt
│ ├── Destined to be Loved by Villains/
│ │ └── DAV-Update.txt
│ ├── Emperors Domination/
│ │ ├── ED-6600-6609.txt
│ │ ├── ED-6610-6635.txt
│ │ └── ED-Update.txt
│ ├── Martial God Asura/
│ │ ├── MGA-6319-6335.txt
│ │ └── MGA-Update.txt
│ └── The Steward Demonic Emperor/
│ ├── SDE-0690-0799.txt
│ ├── SDE-0800-0899.txt
│ ├── SDE-0900-0999.txt
│ ├── SDE-1000-1199.txt
│ └── SDE-1200-1343.txt
├── .gitignore
├── README.md
├── index.html
├── novels.json
└── style.css

- `content/`: Contiene las carpetas de cada novela, y dentro de cada una, los archivos de texto con los capítulos o actualizaciones.
- `novels.json`: Archivo de configuración que lista las novelas disponibles y sus rutas de contenido.
- `index.html`: (Asumo) Un archivo HTML para visualizar el contenido de las novelas en un navegador.
- `style.css`: (Asumo) Un archivo CSS para estilizar la página HTML.
- `.gitignore`: Define los archivos y carpetas que Git debe ignorar.
- `README.md`: Este archivo, que proporciona una descripción del proyecto.

## Cómo Usar

Para acceder a las novelas, puedes:

1.  **Clonar el repositorio:** Si aún no lo has hecho, clona este repositorio en tu máquina local.
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```
2.  **Navegar por los archivos:** Explora las carpetas dentro de `content/` para encontrar la novela que deseas leer y sus archivos de texto correspondientes.
3.  **Usar `index.html`:** Si `index.html` está configurado para mostrar las novelas, puedes abrirlo en tu navegador para una experiencia de lectura más estructurada.
    Este README.md proporciona una visión general del proyecto, enumera las novelas disponibles y explica la estructura de directorios y cómo usar los archivos.

# Mi Proyecto Web

Este es un proyecto de prueba para aprender el flujo entre **Git** y **GitHub**, trabajando con repositorios locales y remotos. Utilizando además diferentes ramas para cada mejora y haciendo uso de los Pull Requests.

## Contenido
- [Instalación](#1-instalación)
- [Estructura](#2-estructura)
- [Mejoras implementadas](#3-mejoras-implementadas)

## 1. Instalación

Para configurar mi proyecto y sincronizarlo entre mi máquina local y GitHub, seguí estos pasos:

1. **Creé mi repositorio local**  
   - Inicialicé Git en la carpeta de mi proyecto:  
     ```bash
     git init
     ```
   - Añadí mis archivos y realicé el primer commit:  
     ```bash
     git add .
     git commit -m "Primer commit"
     ```

2. **Abrí mi repositorio en GitHub**  
   - Entré en mi cuenta de [GitHub](https://github.com).  
   - Creé un nuevo repositorio (sin README ni archivos iniciales para evitar conflictos).  
   - Copié la URL del repositorio remoto (ejemplo: `https://github.com/eloycompes/mi-proyecto-web`).

3. **Sincronicé mi repositorio local con GitHub**  
   - Vinculé el repositorio remoto:  
     ```bash
     git remote add origin https://github.com/eloycompes/mi-proyecto-web
     ```
   - Subí mi rama principal al remoto:  
     ```bash
     git branch -M main
     git push -u origin main
     ```

De esta forma dejé mi proyecto sincronizado: cada cambio que hago en local lo subo con `git push`, y cualquier actualización en GitHub la traigo con `git pull`.


## 2. Estructura

Mi repositorio está organizado de la siguiente manera:

```plaintext
mi-proyecto-web/
├── index.html
├── .gitignore
└── README.md
```

### index.html
En este archivo he creado la página principal de mi proyecto:

- Contiene un título: **"Mi Proyecto Web"**.
- Incluye un navegador con las opciones **Inicio** y **Contacto**.
- Añadí una sección extra con una **tabla de horarios de clases**.

### .gitignore
Este archivo se utiliza para indicar a Git qué ficheros o carpetas no deben ser rastreados ni subidos al repositorio remoto.  
Por ejemplo, se ignoran archivos temporales, configuraciones locales o dependencias que no son necesarias en GitHub.

### README.md
Aquí documento mi proyecto, explicando cómo instalarlo, su estructura y las mejoras que voy implementando.  
Este archivo se muestra por defecto en la página principal del repositorio en GitHub.


## 3. Mejoras implementadas

A lo largo del desarrollo de este proyecto he ido aplicando distintas mejoras, organizadas por ramas y validadas mediante Pull Requests:

- [x] Creé el repositorio local y lo vinculé con GitHub.
- [x] Añadí el archivo `index.html` con estructura básica y contenido inicial.
- [x] Implementé un navegador con enlaces a Inicio y Contacto.
- [x] Incorporé una tabla de horarios de clases en una sección adicional.
- [x] Añadí el archivo `.gitignore` para excluir archivos innecesarios del control de versiones.
- [x] Redacté el archivo `README.md` explicando el propósito y la estructura del proyecto.
- [ ] Crear una rama para añadir estilos con CSS.
- [ ] Implementar validación de formularios en la sección de Contacto.
- [ ] Añadir pruebas unitarias para verificar el funcionamiento de componentes clave.
- [ ] Documentar el uso de ramas y Pull Requests en el flujo de trabajo.


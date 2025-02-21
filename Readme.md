# 🌍 **Proyecto: Desarrollo de 55 Páginas Web con HTML y CSS**

## 🔥 **Descripción**

Este proyecto consiste en la creación de **55 páginas web estáticas** utilizando **HTML y CSS**. La gestión se realizará con **GitHub Projects** mediante un **flujo Kanban**, asegurando una organización eficiente del desarrollo de cada página.

💡 **Objetivo:** Desarrollar un conjunto de páginas bien diseñadas, responsivas y accesibles.

------

## 🚀 **¿Cómo comenzar?**

1️⃣ **Clona el repositorio** en tu computadora:

```
bashCopiarEditargit clone https://github.com/usuario/proyecto-55-paginas.git
cd proyecto-55-paginas
```

2️⃣ **Abre el proyecto** en tu editor de código favorito (VSCode, Sublime, Atom, etc.).
3️⃣ **Accede a GitHub Projects** para ver el tablero Kanban y asignarte tareas.

🔗 **Tablero Kanban en GitHub Projects:** [📌 Enlace al tablero](https://github.com/usuario/proyecto-55-paginas/projects)

------

## 🗂 **Gestión con GitHub Projects (Kanban)**

El proyecto se gestionará con un tablero **Kanban**, incluyendo una vista especial para **Backlog**.

📌 **Estructura del Tablero:**

| 📥 BACKLOG | 🚀 TO DO  | 🛠 IN PROGRESS | ✅ DONE    |
| --------- | -------- | ------------- | --------- |
| Página 51 | Página 1 | Página 10     | Página 5  |
| Página 52 | Página 2 | Página 20     | Página 8  |
| Página 53 | Página 3 | Página 15     | Página 12 |

📍 **Flujo de trabajo:**

1. **BACKLOG:** Ideas y tareas futuras que aún no están en desarrollo.
2. **TO DO:** Páginas listas para ser desarrolladas.
3. **IN PROGRESS:** Páginas en las que se está trabajando.
4. **DONE:** Páginas terminadas y revisadas.

💡 **Cómo usarlo:**
✔ Si encuentras una idea interesante, muévela de **Backlog → To Do**.
✔ Si tomas una tarea, pásala a **In Progress**.
✔ Cuando termines, pásala a **Done**. 🎉

------

## 🎨 **Diseño y Estilos**

Las páginas seguirán un diseño moderno y responsive con:

✅ **Colores modernos y accesibles**
✅ **Tipografías elegantes (Google Fonts)**
✅ **Diseño con Flexbox y Grid**

🎨 **Paleta de colores recomendada:**

- 🔵 Azul: `#3498db`
- 🌿 Verde: `#2ecc71`
- ⚫ Gris oscuro: `#2c3e50`

------

## 📂 **Estructura del Proyecto**

```
bashCopiarEditar/proyecto-55-paginas  
│── /css (Estilos de las páginas)  
│── /img (Imágenes y recursos)  
│── /pages (Páginas individuales)  
│── index.html (Página principal)  
│── README.md  
```

------

## 🛠 **Tecnologías Utilizadas**

✔ **HTML5**
✔ **CSS3 (Flexbox, Grid, Animaciones)**
✔ **GitHub Projects para la gestión**

------

## 📝 **Ejemplo de Código**

📌 **HTML - Sección de una página:**

```
htmlCopiarEditar<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de Página</title>
    <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
    <header>
        <h1>Bienvenido a nuestra página</h1>
    </header>
    <section class="contenido">
        <p>Explora nuestros diseños y estilos únicos.</p>
    </section>
</body>
</html>
```

📌 **CSS - Estilos básicos:**

```
cssCopiarEditarbody {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    text-align: center;
}

header {
    background-color: #3498db;
    color: white;
    padding: 20px;
}
```

------

## 🔥 **Interacción y Contribuciones**

📢 **¿Quieres colaborar?**

1. **Toma una tarea** del tablero Kanban.
2. Crea una **nueva rama** (`git checkout -b nombre-tarea`).
3. **Desarrolla la página** asignada.
4. **Haz un commit y push** (`git push origin nombre-tarea`).
5. **Abre un Pull Request** en GitHub 🚀.

💡 **¿Dudas o ideas?** Comenta en la sección de Issues.

------

## 🐞 **Problemas Comunes y Soluciones**

❌ **El CSS no se aplica correctamente**
✔ Verifica que la ruta en `<link rel="stylesheet" href="css/estilos.css">` sea correcta.

❌ **La página no se ve bien en móviles**
✔ Usa **media queries** en CSS:

```
cssCopiarEditar@media (max-width: 768px) {
    body {
        background-color: lightgray;
    }
}
```

------

## 🤝 **Contribuyentes**

🎯 Si deseas contribuir, sigue las normas del proyecto y respeta las guías de código.

📌 **¡Todos son bienvenidos a colaborar!**

------

## 📄 **Licencia**

Este proyecto está bajo la **Licencia MIT**.
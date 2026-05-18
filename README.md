# 💬 README - Sistema de mensajería responsive

## 📌 descripción

Este proyecto corresponde al desarrollo de una interfaz de sistema de mensajería moderna creada con **HTML5** y **CSS3**, utilizando exclusivamente **Flexbox** para la maquetación responsive.

El desafío fue desarrollado para la empresa ficticia **Contact Me SPA**, cuyo objetivo era construir una pantalla de contactos y conversaciones adaptable tanto a dispositivos móviles como a escritorio.

## 🎯 objetivo del proyecto

Construir una interfaz responsive que permita:

- 📱 adaptación automática en móviles
- 💻 visualización correcta en escritorio
- 👤 mostrar usuario activo
- 💬 listar contactos y conversaciones
- 🎨 crear un diseño limpio y moderno
- ⚡ utilizar únicamente Flexbox

##  🛠 Tecnologías utilizadas

| tecnología     | uso                     |
| -------------- | ----------------------- |
| 🌐 HTML5        | estructura semántica    |
| 🎨 CSS3         | estilos y diseño        |
| 📦 Flexbox      | distribución responsive |
| 🔤 Google Fonts | tipografía Roboto       |

## ✨ Características principales

### 📱 Diseño responsive

### El proyecto se adapta automáticamente sin utilizar:

- ❌ media queries
- ❌ Bootstrap
- ❌ frameworks externos

Utilizando:

``` display: flex;
flex-wrap: wrap;
clamp();
min(); ```
```

## 🧩 Funcionalidades implementadas

### 👤 perfil del usuario 

La barra lateral incluye:

- 🖼 foto de perfil
- 🟢 estado activo
- 💬 icono de mensajes
- ☰ menú lateral

## ➕ botón nuevo chat

🎯 centrado completamente con Flexbox

🎨 diseño moderno en color morado

📱 adaptable a distintos tamaños

Todo alineado utilizando Flexbox.

## 🤝 Sección principal 

✋ ilustración central

🧠 mensaje de bienvenida

📍 contenido centrado vertical y horizontalmente

## 📂 estructura del proyecto

``` proyecto/
│
├── index.html
│
├── assets/
│   ├── css/
│   │   └── style.css
│   │
│   └── img/
│       ├── maria.jpg
│       ├── hand.png
│       ├── chat.svg
│       ├── menu.svg
│       └── contactos/ 
```

## 📚 Conceptos aplicados:

Flexbox fue utilizado para:

- ↔ dividir columnas
- 📍 centrar elementos
- 📋 organizar contactos
- 🔄 adaptar contenido automáticamente

## 📐 Responsive design

El comportamiento adaptable fue logrado mediante:


```flex: 1 1 320px;
width: min();
font-size: clamp();
```

## ✅ requerimientos cumplidos

| requerimiento                     | estado |
| --------------------------------- | ------ |
| 📦 uso de flexbox en columnas      | ✅      |
| 🎯 centrado de contenido principal | ✅      |
| 📋 listado vertical de contactos   | ✅      |
| 🖼 alineación de imágenes y textos | ✅      |
| ➕ botón nuevo chat centrado       | ✅      |
| 👤 estado e iconos del usuario     | ✅      |

## 🖥 Vista previa

### 💻 escritorio

- sidebar lateral
- sección principal amplia
- diseño limpio y profesional

### 📱 Móviles

- estructura adaptable
- contenido centrado
- visualización optimizada



# Encriptador de texto · JavaScript

Aplicación web que **cifra y descifra mensajes** con un conjunto de reglas de sustitución, construida con HTML, CSS y JavaScript puro (sin librerías). Fue mi solución al **Challenge Encriptador de Texto** del programa **Oracle Next Education (ONE) + Alura**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
[![GitHub Pages](https://img.shields.io/github/deployments/juan-roserodev/text-encryptor-js/github-pages?label=GitHub%20Pages&logo=githubpages)](https://juan-roserodev.github.io/text-encryptor-js/)
[![Licencia MIT](https://img.shields.io/badge/licencia-MIT-green?style=flat)](LICENSE)

### 🔗 [Ver demo en vivo](https://juan-roserodev.github.io/text-encryptor-js/)

![Captura del encriptador de texto](docs/captura.png)

---

## 🎯 Descripción

El reto consistía en practicar lógica de programación y manipulación del DOM: recibir un texto, transformarlo con reglas fijas y mostrar el resultado con una interfaz clara y responsive.

**Reglas de cifrado**

| Letra | Se reemplaza por |
|---|---|
| `e` | `enter` |
| `i` | `imes` |
| `a` | `ai` |
| `o` | `ober` |
| `u` | `ufat` |

Ejemplo: `gato` → `gaitober`

## ✨ Características

- Cifrado y descifrado con un clic.
- **Validación de entrada:** solo acepta letras minúsculas sin acentos y avisa al usuario si el texto no cumple.
- Botón para **copiar el resultado** al portapapeles (Clipboard API).
- Botón para limpiar y volver al estado inicial.
- Página de instrucciones y diseño adaptable a móvil, tablet y escritorio.

## 🛠️ Stack tecnológico

- **HTML5** semántico
- **CSS3** (Flexbox, media queries)
- **JavaScript (ES6)**: eventos, manipulación del DOM, expresiones regulares y Clipboard API

## 🗂️ Estructura

```
text-encryptor-js/
├── index.html              # Interfaz principal
├── HTML/instrucciones.html # Página de instrucciones
├── CSS/styles.css
├── JS/app.js               # Lógica de cifrado, validación y eventos
└── IMG/
```

## 🚀 Uso local

No necesita instalación ni dependencias:

```bash
git clone https://github.com/juan-roserodev/text-encryptor-js.git
cd text-encryptor-js
```

Abre `index.html` en el navegador (o usa la extensión *Live Server* de VS Code).

## ✅ Buenas prácticas aplicadas

- Separación de estructura (HTML), presentación (CSS) y comportamiento (JS).
- Validación del texto antes de procesarlo, con mensajes claros para el usuario.
- Resultado mostrado con `innerText`, de modo que el texto ingresado no se interpreta como HTML.
- Funciones pequeñas y con un solo propósito (`encriptarTexto`, `desencriptarTexto`, `validarTexto`).

## 👤 Autor

**Juan David Rosero Reyes** · Desarrollador web full stack

[![Portafolio](https://img.shields.io/badge/Portafolio-juan--roserodev.github.io-0A66C2?style=flat&logo=githubpages&logoColor=white)](https://juan-roserodev.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-david--reyes--dev-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-reyes-dev)
[![Email](https://img.shields.io/badge/Email-juan.rosero21%40hotmail.com-0078D4?style=flat&logo=microsoftoutlook&logoColor=white)](mailto:juan.rosero21@hotmail.com)

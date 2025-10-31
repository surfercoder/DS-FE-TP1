# DS-FE-TP1
Desarrollo Software - Frontend - Trabajo Practico 1

## 📋 Descripción del Proyecto
Primera página web HTML creada como ejercicio práctico para aprender los fundamentos de HTML.

## 🎯 Objetivos del Ejercicio
- Crear la estructura básica de un documento HTML
- Utilizar etiquetas de encabezado y párrafos
- Implementar listas
- Insertar imágenes y enlaces
- Comprender el uso de atributos HTML

## 🛠️ Tecnologías Utilizadas
- **HTML5**: Lenguaje de marcado para estructurar el contenido web

## 📚 Conceptos Aprendidos

### 1. Estructura Básica de HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <!-- Metadatos -->
</head>
<body>
    <!-- Contenido visible -->
</body>
</html>
```

**Elementos clave:**
- `<!DOCTYPE html>`: Declara que el documento es HTML5
- `<html>`: Elemento raíz que contiene todo el documento
- `<head>`: Contiene metadatos (información sobre la página)
- `<body>`: Contiene el contenido visible de la página

### 2. Metadatos en el `<head>`
- `<meta charset="UTF-8">`: Define la codificación de caracteres (permite usar ñ, tildes, etc.)
- `<meta name="viewport">`: Hace la página responsive para dispositivos móviles
- `<title>`: Define el título que aparece en la pestaña del navegador

### 3. Etiquetas de Encabezado
- `<h1>`: Encabezado principal (el más importante)
- `<h2>`: Encabezado secundario
- Existen desde `<h1>` hasta `<h6>` (de mayor a menor importancia)

### 4. Párrafos y Texto
- `<p>`: Define un párrafo de texto
- `<small>`: Texto en tamaño reducido
- `&copy;`: Entidad HTML para el símbolo de copyright ©

### 5. Listas
- `<ul>`: Lista no ordenada (con viñetas)
- `<li>`: Elemento de lista individual
- También existe `<ol>` para listas ordenadas (numeradas)

### 6. Imágenes
```html
<img src="url" alt="descripción" width="400" height="300">
```

**Atributos importantes:**
- `src`: URL o ruta de la imagen (obligatorio)
- `alt`: Texto alternativo si la imagen no carga (obligatorio para accesibilidad)
- `width` y `height`: Dimensiones de la imagen

### 7. Enlaces
```html
<a href="https://ejemplo.com" target="_blank">Texto del enlace</a>
```

**Atributos importantes:**
- `href`: URL de destino (obligatorio)
- `target="_blank"`: Abre el enlace en una nueva pestaña

### 8. Elementos Semánticos
- `<footer>`: Define el pie de página del documento

### 9. Comentarios HTML
```html
<!-- Este es un comentario que no se muestra en el navegador -->
```

## 🚀 Cómo Visualizar la Página

1. Abre el archivo `index.html` en tu navegador web
2. Puedes hacerlo de dos formas:
   - Doble clic sobre el archivo
   - Clic derecho → "Abrir con" → Seleccionar tu navegador preferido

## ✅ Pasos Completados

- [x] **Paso 1**: Estructura básica HTML con `<html>`, `<head>` y `<body>`
- [x] **Paso 2**: Contenido principal con `<h1>`, `<h2>`, párrafo y lista de hobbies
- [x] **Paso 3**: Elementos interactivos con imagen (`<img>`) y enlace (`<a>`)
- [x] **Paso 4**: Archivo listo para visualizar en el navegador

## 💡 Buenas Prácticas Aplicadas

1. **Uso de `lang="es"`**: Indica que el contenido está en español
2. **Atributo `alt` en imágenes**: Mejora la accesibilidad
3. **Comentarios en el código**: Facilita la comprensión del código
4. **Indentación correcta**: Hace el código más legible
5. **Estructura semántica**: Uso de etiquetas apropiadas para cada tipo de contenido

## 📖 Recursos Adicionales

- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)

---

**Autor**: Estudiantes UTN - Desarrollo de Software  
**Fecha**: Octubre 2025

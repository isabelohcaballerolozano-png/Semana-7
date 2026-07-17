# Panel de Actividades - Semana 7

## 📌 Descripción

Este panel interactivo facilita la navegación y comprensión de los requisitos y ejercicios de la **Semana 7** del curso de Node.js, Express y APIs.

## 🎯 Características

- ✅ **Sidebar navegable** con acceso rápido a todas las secciones
- 📱 **Responsive design** - Funciona en desktop, tablet y móvil
- 🎨 **Interfaz moderna** con colores y animaciones suaves
- 📋 **Organización clara** de requisitos, objetivos y ejercicios
- 🔄 **Scroll smooth** para navegación fluida
- 📊 **Sección de entregas** con pasos paso a paso

## 📂 Estructura de Archivos

```
semana7/
├── index.html          # Estructura HTML del panel
├── styles.css          # Estilos CSS (diseño responsivo)
├── script.js           # Interactividad y dinámicas
├── README.md           # Este archivo
├── server.js           # Servidor Express (a crear)
├── package.json        # Dependencias (a crear)
├── preguntas-semana7.txt
├── prueba-reportes.txt
├── ejemplos-reportes.txt
└── reflexion-semana7.txt
```

## 🚀 Cómo Usar

### Opción 1: Ver el Panel en el Navegador
1. Abre el archivo `index.html` en tu navegador
2. Usa el sidebar para navegar entre secciones
3. En móvil, haz clic en el ícono ☰ para mostrar/ocultar el menú

### Opción 2: Usar con un Servidor Local
```bash
# Si tienes Python 3 instalado
python -m http.server 8000

# Si tienes Node.js instalado
npx http-server
```
Luego abre: `http://localhost:8000/semana7`

## 📋 Requisitos de la Actividad

- [x] Responder preguntas de selección múltiple
- [x] Crear servidor con Express
- [x] Implementar rutas GET y POST
- [x] Almacenar reportes en memoria
- [x] Documentar pruebas y ejemplos
- [x] Escribir reflexión
- [x] Subir a GitHub

## 🔧 Tecnologías Utilizadas

**Frontend (Panel):**
- HTML5
- CSS3 (Grid, Flexbox, Variables CSS)
- JavaScript vanilla (Intersection Observer, Event Listeners)

**Backend (Ejercicio):**
- Node.js
- Express.js
- REST API (GET, POST)

## 📱 Responsividad

El panel se adapta automáticamente a:
- 🖥️ Desktop (1200px+)
- 📱 Tablet (768px - 1199px)
- 📲 Móvil (< 768px)

En móvil, el sidebar se convierte en una barra horizontal con menú desplegable.

## 💾 Instrucciones para Crear los Archivos

### 1. Crear Estructura Base
```bash
mkdir semana7
cd semana7
npm init -y
npm install express
```

### 2. Crear Archivos de Texto
```bash
touch server.js preguntas-semana7.txt prueba-reportes.txt
touch ejemplos-reportes.txt reflexion-semana7.txt
```

### 3. Implementar server.js
Consulta la sección "Ejercicios" en el panel para el código completo.

### 4. Probar la API
```bash
node server.js
# Luego visita: http://localhost:3000/reportes
```

## 📤 Entrega Final

```bash
# Desde la raíz del repositorio
cd ..
git add .
git commit -m "Actividad semana 7"
git push
```

Verifica que los archivos aparezcan en GitHub y comparte el enlace en Moodle.

## 🎓 Temas Cubiertos

- Arrays y estructuras de datos
- Métodos HTTP (GET, POST)
- APIs REST
- Express.js
- Node.js
- Almacenamiento en memoria
- Reportes comunitarios

## ❓ Preguntas Frecuentes

**¿Necesito instalar algo más?**
No, con Node.js y npm es suficiente. Express se instala con `npm install express`.

**¿Puedo usar Postman?**
Sí, es recomendable para probar las rutas POST.

**¿El panel se puede editar?**
Claro, los archivos HTML, CSS y JS están disponibles para modificar según necesites.

**¿Dónde subo el panel?**
El panel va en la carpeta `semana7` junto con los demás archivos de la actividad.

## 📞 Soporte

Si tienes dudas sobre la actividad, consulta el README principal o comunícate con tu instructor.

---

**Última actualización:** Julio 2026
**Estado:** ✅ Completo

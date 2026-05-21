# 🌍 Programadores para la Paz – Mini-sitio Comunitario

> Proyecto comunitario desarrollado durante la **Semana 5**  
> Clases 21 a 25

Mini-sitio web orientado a la difusión responsable de información comunitaria mediante una API propia y un sistema básico de organización editorial.

---

# 📌 Propósito del proyecto

Construir progresivamente un mini-sitio comunitario que permita:

- Mostrar mensajes comunitarios
- Gestionar un calendario editorial
- Consumir información desde una API propia
- Mantener una comunicación clara y verificable
- Aplicar buenas prácticas básicas de desarrollo web

El proyecto combina tecnología y comunicación responsable para apoyar procesos de participación ciudadana.

---

# 🏛️ Enfoque ciudadano

Este proyecto trabaja principios como:

- ✅ Difusión responsable
- ✅ Calendario editorial
- ✅ Revisión de fuentes
- ✅ Consistencia comunicativa
- ✅ Moderación editorial básica
- ✅ Accesibilidad mínima
- ✅ Minimización de datos visibles
- ✅ Lenguaje responsable y no estigmatizante
- ✅ Transferencia tecnológica
- ✅ Documentación como transparencia

---

# 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| Node.js | Servidor backend |
| Express | Manejo de rutas |
| HTML | Estructura del sitio |
| CSS | Estilos visuales |
| JavaScript | Interactividad |
| JSON | Almacenamiento de datos |
| Git | Control de versiones |
| GitHub | Trabajo colaborativo |

---

# 📂 Estructura del proyecto

```text
.
├── server.js
├── package.json
├── data/
│   ├── mensajes.json
│   └── calendario-editorial.json
├── public/
│   ├── index.html
│   ├── app.js
│   └── styles.css
├── semana5/
└── instrucciones/
```

---

# ⚙️ Instalación

## 1️⃣ Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

## 2️⃣ Entrar al proyecto

```bash
cd programadores-para-la-paz-mini-sitio-comunitario
```

## 3️⃣ Crear rama personal

```bash
git checkout -b nombres_apellidos
```

## 4️⃣ Instalar dependencias

```bash
npm install
```

---

# ▶️ Ejecución del proyecto

## Iniciar el servidor

```bash
npm run sitio
```

## Abrir en el navegador

```text
http://localhost:3000
```

---

# 🔌 Rutas de la API

| Método | Ruta | Descripción |
|---|---|---|
| GET | `/api/mensajes` | Entrega mensajes comunitarios |
| GET | `/api/calendario` | Entrega piezas del calendario editorial |
| GET | `/api/resumen` | Entrega un resumen del proyecto |
| POST | `/api/login` | Ruta pedagógica de login |
| GET | `/api/revision-editorial` | Esta sección permite probar un middleware simple |

---

# 🔐 Login pedagógico

⚠️ **Importante**

Esta ruta existe únicamente con fines educativos.

- No representa autenticación real
- No debe utilizarse en producción
- No almacena sesiones reales
- No implementa seguridad avanzada

# 🧩 Middleware simple

El proyecto incluye una ruta protegida pedagógica para demostrar el funcionamiento básico de un middleware en Express.

Primero se debe realizar el login pedagógico y obtener un token de demostración. Luego, ese token permite acceder a la sección de revisión editorial protegida.

## Ruta protegida pedagógica

La ruta protegida permite probar un middleware simple encargado de verificar el acceso a contenido editorial.

## Revisión editorial protegida

```text
Acceso permitido a la revisión editorial pedagógica.
```

## Credenciales de demostración

```text
usuario: docente
clave: demo
```

---

# 🌱 Flujo de trabajo con Git

La rama `main` es actualizada por docentes.

Cada estudiante debe trabajar únicamente en su rama personal.

---

## 📥 Al iniciar cada clase

### Ir a main

```bash
git checkout main
```

### Descargar cambios nuevos

```bash
git pull --ff-only origin main
```

### Volver a la rama personal

```bash
git checkout nombres_apellidos
```

### Fusionar cambios actualizados

```bash
git merge main
```

---

## 📤 Al terminar cada clase

### Revisar archivos modificados

```bash
git status
```

### Agregar cambios

```bash
git add .
```

### Crear commit

```bash
git commit -m "Mensaje claro del avance"
```

### Subir cambios

```bash
git push
```

---

# 🤖 Uso responsable de IA

La IA puede ayudar a:

- Mejorar redacción
- Organizar pasos
- Explicar errores
- Comprender conceptos técnicos
- Revisar estructura del proyecto
- Detectar errores básicos

## 🚫 No se debe usar IA para publicar

- Credenciales reales
- Tokens reales
- Datos personales
- Información sensible de la comunidad
- Contenido sin verificar

Toda sugerencia generada por IA debe revisarse, probarse y validarse antes de aceptarse.

---

# 📌 Evidencia

La evidencia oficial del proyecto corresponde únicamente al:

✅ Push realizado en la rama personal de GitHub.

## ❌ No se deben entregar

- Capturas de pantalla
- Archivos adicionales
- Enlaces externos
- Entregas por Moodle

---

# 💡 Recomendaciones

- Mantener commits claros y descriptivos
- Probar las rutas antes de hacer push
- Verificar el funcionamiento del servidor
- Documentar cambios importantes
- Evitar subir archivos innecesarios
- Mantener una estructura organizada

---

# 📖 Nota final

Este proyecto busca fortalecer tanto habilidades técnicas como prácticas responsables de comunicación digital y trabajo colaborativo.

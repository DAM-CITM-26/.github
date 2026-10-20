````markdown
# 🎓 DAM-CITM-26

Bienvenidos a la organización de **DAM-CITM-26**.

Utilizaremos esta organización para realizar los ejercicios de clase y crear los repositorios de las prácticas.

Aquí iremos organizando los proyectos que trabajemos durante el curso.

---

## 🚀 Guía rápida y consejos

En esta sección encontrarás las instrucciones básicas para preparar el entorno, crear un proyecto y arrancarlo en el navegador.

### 🔎 1. Comprobar que Node.js y npm están instalados

Antes de empezar, comprueba que el ordenador de clase tiene instalados [Node.js](https://nodejs.org/) y npm.

Abre PowerShell y ejecuta estos comandos:

```powershell
node -v
npm -v
```

Cada comando debe mostrar el número de versión correspondiente.

> ⚠️ Si alguno no muestra la versión o aparece un error indicando que el comando no se reconoce, sigue la guía de la clase 9 antes de continuar.

---

### 📂 2. Crear un proyecto

Abre PowerShell desde una carpeta en la que tengas permisos de escritura, por ejemplo, Documentos.

Ejecuta el siguiente comando, sustituyendo `nombre-del-proyecto` por el nombre que quieras darle:

```powershell
npm create vite@latest nombre-del-proyecto
```

Cuando termine, se habrá creado una nueva carpeta con el nombre del proyecto y todos sus archivos dentro.

#### ⚙️ Respuestas para el asistente de Vite

Selecciona estas opciones cuando el asistente las solicite:

| Opción | Respuesta |
| :--- | :--- |
| Package name | El nombre de tu proyecto, por ejemplo, `nombre-del-proyecto` |
| Framework | React |
| Variant | JavaScript |
| Linter | ESLint |
| Install with npm | Yes para instalar las dependencias ahora, o No para hacerlo después |
| Start now | Yes para iniciar el servidor de desarrollo ahora, o No para hacerlo después |

#### 📦 Instalar las dependencias manualmente

Si no has elegido instalar las dependencias durante el asistente, entra en la carpeta del proyecto y ejecuta:

```powershell
cd nombre-del-proyecto
npm install
```

> 💡 La instalación inicial de dependencias solo hace falta realizarla una vez al crear el proyecto; no es necesario repetirla cada vez que quieras arrancarlo.

---

### 🌐 3. Arrancar la web en el navegador

Abre PowerShell desde la carpeta del proyecto y ejecuta:

```powershell
npm run dev
```

Este comando inicia un servidor de desarrollo local. En la terminal aparecerá un enlace para acceder a la web.

Mantén pulsada la tecla Ctrl y haz clic en el enlace para abrirlo en el navegador.

> 📌 Deja la terminal abierta mientras trabajas. Cada vez que se cierre el servidor de desarrollo, tendrás que volver a ejecutar `npm run dev` para arrancarlo de nuevo.
````

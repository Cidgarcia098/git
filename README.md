# 🚀 Mi Primer Repositorio con Git y GitHub

¡Hola! Bienvenido a mi repositorio de presentación. Este proyecto fue creado con el objetivo de configurar correctamente mi entorno de trabajo de Git en **Windows 11** y demostrar el dominio de los comandos fundamentales de control de versiones.

---

## 👤 Sobre Mí

- 💻 **Desarrollador en formación:** Aprendiendo tecnologías web y control de versiones.
- ⚙️ **Entorno de Trabajo:** Windows 11 (UCRT64 / Git Bash) + VS Code.
- 📌 **Estado:** Configuración de Git global completada y repositorio sincronizado exitosamente.

---

## 🛠️ Configuración de Mi Entorno Git

Para preparar mi entorno de desarrollo local en Windows 11, apliqué las mejores prácticas ejecutando la siguiente configuración global:

```bash
# 1. Identidad de usuario
git config --global user.name "Tu Nombre"
git config --global user.email "tu_email@ejemplo.com"

# 2. Rama por defecto estándar
git config --global init.defaultBranch main

# 3. Manejo correcto de saltos de línea para Windows
git config --global core.autocrlf true

# 4. Editor de texto predeterminado
git config --global core.editor "code --wait"

# 5. Colores activos en la interfaz de línea de comandos
git config --global color.ui true
```

---

## 📌 Guía Rápida de Comandos Git

A continuación se muestra el flujo de trabajo básico utilizado para crear y actualizar este repositorio:

| Comando | Descripción |
| :--- | :--- |
| `git init` | Inicializa un nuevo repositorio Git en la carpeta actual. |
| `git status` | Muestra el estado del árbol de trabajo y del área de preparación (*staging area*). |
| `git add README.md` | Agrega el archivo especificado al *staging area*. |
| `git commit -m "mensaje"` | Guarda una foto (*snapshot*) de los cambios en el historial local. |
| `git branch -M main` | Asegura que la rama principal sea renombrada a `main`. |
| `git remote add origin <URL>` | Vincula el repositorio local con un repositorio remoto en GitHub. |
| `git push -u origin main` | Sube los commits locales al repositorio remoto y guarda el rastreo de la rama. |

---

## 📈 Próximos Pasos

- [x] Configurar Git localmente.
- [x] Crear repositorio local y subir el primer commit a GitHub.
- [ ] Practicar el uso de ramas (`git branch`, `git checkout`, `git merge`).
- [ ] Colaborar mediante *Pull Requests* y resolver conflictos de fusión.

---

*Proyecto creado como parte de la ruta de aprendizaje en Git & GitHub.*
# Sistema de Gestión Educativa - Nuevas Tecnologías

## 👥 Integrantes del Equipo
* María Fernanda Correa 
* Alejandro Gómez
* Nayla Isabela Mesa 
* Juan David López 

---

## 📝 Descripción del Proyecto
Sistema web de gestión educativa desarrollado para la asignatura de Nuevas Tecnologías de Programación en el CESDE.

---

## 🌳 Estrategia de Ramas (GitFlow)
Seguimos la metodología GitFlow para la organización del código:
* `main`: Rama principal de producción. Contiene únicamente código estable.
* `develop`: Rama principal de desarrollo donde se integran todas las nuevas funcionalidades.
* `feature/<nombre-tarea>`: Ramas independientes para construir funcionalidades específicas sin afectar el código base.

---

## 💬 Convenciones para Commits
Utilizamos el estándar **Conventional Commits** para mantener un historial claro:
* `feat:` Para nuevas funcionalidades (ej: `feat: crea pantalla de login`).
* `fix:` Para corrección de errores (ej: `fix: corrige error de validación`).
* `docs:` Para cambios en documentación (ej: `docs: actualiza el README`).
* `style:` Para cambios de formato/diseño que no alteran la lógica.

---

## 🔀 Reglas para Pull Requests y Fusiones (Merge)
1. Queda prohibido realizar commits directos sobre las ramas `main` o `develop`.
2. Todo nuevo desarrollo debe hacerse en una rama `feature/` y enviarse hacia `develop` mediante un **Pull Request (PR)**.
3. Para realizar una fusión (merge), el PR debe ser revisado y aprobado por al menos **un integrante del equipo**.

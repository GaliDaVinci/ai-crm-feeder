# 📝 Guía rápida: Cómo escribir buenos mensajes de commit

---

## ✨ Buena práctica: usa **Conventional Commits**

Es un formato estándar que, además, te permite **generar changelogs automáticos** si luego lo necesitas.

### 📌 Estructura básica
tipo(alcance): descripción corta en presente
[cuerpo opcional explicando el porqué]

---

## 🏷️ Tipos más comunes

----------------------------------------------------------------------
| Tipo       | Cuándo usarlo                                         |
|------------|-------------------------------------------------------|
| `feat`     | Agregas una funcionalidad nueva                       |
----------------------------------------------------------------------
| `fix`      | Corriges un bug                                       |
----------------------------------------------------------------------
| `refactor` | Cambias código sin alterar comportamiento             |
----------------------------------------------------------------------
| `docs`     | Cambios en documentación (README, comentarios)        |
----------------------------------------------------------------------
| `chore`    | Tareas de mantenimiento (gitignore, dependencias)     |
----------------------------------------------------------------------
| `test`     | Agregas o corriges pruebas                            |
----------------------------------------------------------------------
| `wip`      | Avance a medias, aún no funcional (úsalo con cuidado) |
----------------------------------------------------------------------

---

## 💡 Ejemplos prácticos
----------------------------------------------------------------------
| Comando de commit                                       | Tipo     |
|---------------------------------------------------------|----------|
| `chore: agregar .gitignore para Django`                 | chore    |
----------------------------------------------------------------------
| `docs: crear README inicial del proyecto`               | docs     |
----------------------------------------------------------------------
| `feat(auth): agregar login de usuarios con Django`      | feat     |
----------------------------------------------------------------------
| `feat(captura): crear modelo Cliente y formulario...`   | feat     |
----------------------------------------------------------------------
| `feat(ia): integrar extracción de datos con API de IA`  | feat     |
----------------------------------------------------------------------
| `fix(espocrm): corregir autenticación en cliente...`    | fix      |
----------------------------------------------------------------------
| `refactor(captura): mover lógica de validación a...`    | refactor |
----------------------------------------------------------------------
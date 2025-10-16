# 🚀 ShiftPilot


🌐 Acceso al proyecto:
El código fuente completo de ShiftPilot Server se encuentra en un repositorio privado.
Podés solicitar acceso o más información desde el enlace o contacto debajo 👇

🔗 Repositorio privado (solicitar acceso): github.com/chope-dev/Shiftpilot-server

📧 Contacto: santi.jrs.sg@gmail.com

---

**ShiftPilot** es una plataforma web para la gestión de turnos, licencias y reemplazos en empresas medianas. Permite a empleados, supervisores y administradores coordinar horarios de trabajo de forma eficiente, transparente y segura.

> Tecnologías: Next.js · Node.js (Express) · MongoDB · Docker · TypeScript


## 📦 Características principales

- 🗓️ Gestión visual de turnos laborales
- 🔁 Sistema de reemplazos entre empleados
- 📝 Solicitud y aprobación de licencias
- 👥 Roles de usuario: Empleado · Manager · Admin
- 🔔 Notificaciones automáticas por cambios
- 📊 Dashboard con estadísticas de asistencia y uso

---

## ⚙️ Tecnologías utilizadas

| Capa | Stack |
|------|-------|
| **Frontend** | Next.js 14 · TypeScript · Tailwind CSS |
| **Backend** | Node.js · Express · MongoDB · Mongoose |
| **Seguridad** | JWT · Bcrypt · Helmet · Rate limiting |
| **DevOps** | Docker · GitHub Actions · CI/CD |
| **Arquitectura** | Capas limpias · MVC · Modular · Multitenant-ready |

---

## 🧱 Arquitectura del proyecto

```bash
shiftpilot/
├── client/           # Frontend (Next.js)
└── server/           # Backend (Express + MongoDB)
    ├── controllers/
    ├── routes/
    ├── models/
    ├── services/
    ├── middlewares/
    └── utils/


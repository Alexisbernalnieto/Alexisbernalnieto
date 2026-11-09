# Alexis Bernal Nieto

Desarrollador de software en Querétaro, México. Trabajo en **.NET y SQL Server**: sistemas internos que una empresa usa todos los días para operar.

Hoy soy Desarrollador IT en **PAC by ProAmpac México**. Dos de los sistemas que construí están en producción y los usan áreas completas — ventas, costos, dirección y las casetas de vigilancia de dos plantas. No son proyectos de práctica: si se caen, me llaman a mí.

El código de esos dos es de la empresa, así que no está en este perfil. Abajo está lo que sí puedo mostrar.

---

## Lo que mantengo en producción

### BPM de cotizaciones
`ASP.NET MVC 5` · `Entity Framework 6` · `SQL Server` · `Razor` · `IIS`

Todo el proceso de cotización entre Ventas, Costos y Dirección. Antes vivía en Excel y correo; hoy lo usan a diario 12 roles distintos.

- Flujo de aprobación por rol: Ventas solicita, Costos pone precios, Dirección aprueba. Al aprobar quedan congelados el tipo de cambio, los costos y la utilidad — el histórico no se mueve aunque cambien los precios después.
- Tableros por rol, notificaciones SMTP por template HTML, oferta comercial en PDF y reportes de ventas, márgenes y tiempos de ciclo.
- Arquitectura por capas (Controller → Service → Repository → UnitOfWork) con inyección de dependencias en Unity y pruebas unitarias en MSTest sobre la lógica de negocio.
- Refactor del servicio más grande del sistema: de **4,396 a 1,185 líneas**, separado en 5 servicios por dominio con interfaz propia, sin cambiar comportamiento — verificado línea por línea contra el original.
- Publicación en IIS, mantenimiento, resolución de fallas y soporte directo a los usuarios.

### Plataforma de control de acceso industrial
`ASP.NET MVC` · `SQL Server` · `impresoras Zebra` · `UI para tablet`

Reemplazó la bitácora de papel de la caseta. Los guardias la usan en tablets en dos plantas.

- 13 módulos (visitantes, transportistas, paquetería, vigilantes, citas, actos inseguros) que siguen el estado de cada persona desde que llega hasta que sale.
- Firma y foto digital, y **etiquetas Zebra con QR** para que alguien entre a la segunda planta sin volver a capturar sus datos.
- Panel por planta: quién está adentro ahora, citas del día y tablero para gerencia. Reportes a Excel.
- Inicio de sesión, permisos por rol y protección de los archivos subidos.
- Interfaz diseñada para tablet y para capturar rápido de pie en la caseta, no para escritorio.

---

## Repos de este perfil

| Proyecto | Qué es | Stack |
|---|---|---|
| [BarberiaApp](https://github.com/Alexisbernalnieto/BarberiaApp) | Citas y pagos para barberías, multi-sucursal. Equipo de 4; a mi cargo el portal de administración, la migración de datos, facturación y correos. | React Native (Expo), TypeScript, Firebase, Cloud Functions, Stripe |
| [pizzeria](https://github.com/Alexisbernalnieto/pizzeria) | Pedidos y administración para una pizzería, contenerizado de punta a punta. | React 19, Vite, Flask, Docker Compose, nginx |
| [Piko](https://github.com/Alexisbernalnieto/Piko) | PWA para entrada y salida de órdenes en restaurante; la idea es que un mesero capture en segundos. | FastAPI, Flet, PostgreSQL, Vercel |
| [microservicios](https://github.com/Alexisbernalnieto/microservicios) | Descomposición de un monolito de pedidos en servicios independientes detrás de un API gateway. | Node.js, Express |

---

## Stack

Esto es lo que he usado para construir algo, no lo que he leído.

- **Backend:** C#, .NET Framework 4.8, ASP.NET MVC 5, Entity Framework 6, Razor, Node.js, Express, Python (FastAPI, Flask)
- **Datos:** SQL Server, T-SQL, MySQL, Firestore
- **Frontend:** TypeScript, JavaScript, Angular, React, React Native (Expo), jQuery, Bootstrap 5
- **Operación:** IIS, Docker, Firebase Hosting, Vercel, Git, SMTP
- **Arquitectura:** por capas, inyección de dependencias, pruebas unitarias, design systems propios
- **Redes y sistemas:** TCP/IP, routing, switching, VLANs, DHCP, SSH, Linux — Cisco Networking Academy: CCNAv7 (Introduction to Networks + Switching, Routing & Wireless Essentials), NDG Linux Essentials, IT Essentials (PC Hardware & Software), IoT Fundamentals

---

## Formación

**Ingeniería en Desarrollo de Software Multiplataforma** — Universidad Tecnológica de San Juan del Río (UTSJR). Promedio 9.3/10, egreso mayo 2026.

**Beca Embajadores 2025** — movilidad académica a la Université de Franche-Comté (CLA), Besançon, Francia. 16 ECTS.

**SeñaMex IA** (Programa Nuevos Talentos, UTSJR) — reconocimiento de Lengua de Señas Mexicana en tiempo real con TensorFlow, MediaPipe y Jetson Nano. 3.er lugar en Expo FEI Lobo 2024 y publicación en la revista Nthe (CONCYTEQ, febrero 2025).

Español nativo · Inglés B2 (EnglishScore) · Francés (CLA Besançon, 2025)

---

## Contacto

alexisbernalnieto@gmail.com · [LinkedIn](https://www.linkedin.com/in/alexis-bernal-nieto/)

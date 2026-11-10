# Entrega · Fase 2

📄 **Documento:** [F2_Fuentes_Martinez_Ines.pdf](F2_Fuentes_Martinez_Ines.pdf)

## Resumen

- **Modelo:** Nudo se plantea como un **SaaS B2B**. Cada taller se registra como negocio y gestiona sus talleres, sesiones y stock con sus datos separados del resto. La demo tendrá tres negocios de ejemplo: cerámica, pintura y labores.
- **Alcance esencial:** negocios, cuentas con tres perfiles, talleres, sesiones con control de solapamientos, stock común, reglas de material por taller, reserva con elección de material y suplemento, cancelación, vista de la monitora, avisos de stock bajo e historial.
- **Ampliaciones:** avisos por correo, recuperación de contraseña, lista de espera, varias categorías de material por taller y estadísticas.
- **Requisitos:** 24 funcionales y 13 no funcionales (WCAG 2.2 AA, HTTPS, CSRF, bcrypt/Argon2, reservas simultáneas, 360 px a escritorio...).
- **Stack inicial:** React + Vite + React Router · Laravel 13 + Sanctum · PostgreSQL · API REST en JSON.
- **Infraestructura:** desarrollo local con XAMPP y entorno de pruebas propio con Ubuntu Server y Tailscale. Despliegue en Google Cloud Run y Supabase (UE), todo con planes gratuitos.
- **Coste de puesta en marcha:** 0 €. Con clientes reales se financiaría con cuotas de suscripción.

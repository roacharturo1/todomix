# Todomix final
Incluye tienda pública, carrito, pedidos por WhatsApp, panel `/admin`, inventario básico, almacenamiento de pedidos y backend para Botón de Pago Yappy V2.

## Arranque
Node.js 18+. Copia `.env.example` a `.env`, cambia `ADMIN_PASSWORD` y `WHATSAPP`, luego `npm start`.
Abre `http://localhost:3000`; administración: `http://localhost:3000/admin`.

## Pago
La integración de Yappy usa el flujo V2 oficial y mantiene las credenciales en el backend. Para activar cobros reales debes afiliar Todomix a Yappy Comercial y colocar `YAPPY_MERCHANT_ID`, `YAPPY_SECRET_KEY`, dominio HTTPS e IPN. Yappy exige backend para las llamadas de validación/creación de orden.

No compartas aquí la clave secreta.

# CondorTravels · Frontend

Aplicación web para **reservar vuelos**, desarrollada para el **reto SenaSoft**. Cubre todo el flujo: buscar el vuelo, elegir asientos en un mapa del avión, registrar pasajeros y pagar con PayU.

Backend: [RetoSenaSoft](https://github.com/CristianGarcia7/RetoSenaSoft)

## 🧭 Flujo

1. **Buscar vuelos** por origen y destino (`dashboard`).
2. **Elegir asientos** en una cuadrícula del avión que muestra los asientos disponibles, seleccionados y ocupados (`selectSeats`).
3. **Registrar los datos** de los pasajeros (`datosPersonales`).
4. **Pagar** con PayU y ver la confirmación (`pagar`, `paymentResponse`).
5. Consultar **mis reservas**.

Más detalle en [`SEAT_RESERVATION_GUIDE.md`](SEAT_RESERVATION_GUIDE.md).

## 🧱 Stack

Vue 3 · Quasar 2 · Pinia (con estado persistente) · Vue Router · Axios · Vite

## 🚀 Cómo correrlo

Necesitas el [backend](https://github.com/CristianGarcia7/RetoSenaSoft) en `http://127.0.0.1:8000`. Esa URL se configura en `src/plugins/pluginAxios.js`.

```bash
npm install
npm run dev
```

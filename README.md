# 🎲 Simulador Dilema Monty Hall

Este proyecto recrea el famoso **problema de Monty Hall**, pero llevado a una experiencia **gamificada** y colaborativa, ideal para talleres, clases y dinámicas de equipos.  

Los jugadores enfrentan la paradoja: elegir una puerta, el presentador abre otra con una cabra 🐐, y luego deciden si **cambiar** o **mantener** su elección.  
La matemática demuestra que **cambiar duplica la probabilidad de ganar** 🚗.

---

## 🚀 Flujo de la Plataforma

### 👑 Administrador
- Ingresa con su clave única.  
- **Genera una partida** para un cliente:  
  - Indica cantidad de grupos (1–10).  
- Obtiene **dos tipos de links**:  
  - **Instructor:** acceso al dashboard.  
  - **Jugadores:** acceso al juego para cada grupo.  
- Comparte fácilmente los links generados.

### 👨‍🏫 Instructor
- Ingresa con su link de instructor.  
- Visualiza el **Dashboard en vivo**:  
  - Jugadas totales.  
  - Tasa de éxito de los que cambiaron (switch).  
  - Tasa de éxito de los que se quedaron (stay).  
- Se actualiza automáticamente cada **10 segundos**.

### 🎮 Jugadores
- Reciben su link y entran directo al juego.  
- Flujo de juego:  
  1. Seleccionan una puerta.  
  2. El simulador abre una puerta con una cabra 🐐.  
  3. Deciden cambiar o mantener (con temporizador automático).  
  4. Resultado con animación y sonido 🚗🐐.  
  5. Nueva ronda automática (con una **jugada 0 demo** que no suma).  

---

## 📊 Google Sheets Dashboard

Todos los eventos se registran en Google Sheets:
- **links** → control de partidas y accesos.  
- **dashboard** → métricas de resultados:  
  - Total de jugadas.  
  - Ganadas y perdidas (switch / stay).  
  - Tasas de éxito (%).  

---

## 🛠️ Tecnologías

- **Frontend:** HTML + CSS + JavaScript.  
- **Backend:** Google Apps Script (API REST con `doPost` y `doGet`).  
- **Base de datos:** Google Sheets.  
- **Hosting:** GitHub Pages.  

---

## 📂 Estructura del Proyecto


# Simulación de Control de Filas — UTN FRBA

Trabajo Práctico Integrador para **Teoría de Control K-4572**, UTN FRBA.

Autores: Román Brezman – 203.432-3, Jana Nurit Rozenberg - 1636170  
Docente: Prof. Omar Oscar Civale

---

## Descripción

Este proyecto simula el control automático de filas en un sistema de atención al público (ejemplo: mostradores de un aeropuerto). Se emplea un **controlador PD** (Proporcional-Derivativo) para ajustar el número de mostradores activos en función de la demanda variable de clientes, buscando mantener el tiempo de espera en valores aceptables.

Incluye:
- Panel de control para modificar parámetros de la simulación.
- Visualizaciones (gráficos interactivos usando Chart.js).
- Bitácora de eventos con los principales cambios del sistema.

---

## Cómo usar el simulador

1. **Abrir el archivo `simulacion-18.html` en un navegador web.**

   > Si lo ves en GitHub, descárgalo primero.  
   > Alternativamente, si el repositorio tiene habilitado GitHub Pages, accede directamente via  
   > `https://<usuario>.github.io/<repo>/simulacion-18.html`

2. **Usa el panel lateral izquierdo para controlar los parámetros:**
    - **Kp / Kd:** Ganancias del controlador PD.
    - **Pico de demanda (λ) y hora de inicio:** Simulan una hora pico donde la cantidad de clientes aumenta.
    - **Ruido de demanda:** Variabilidad aleatoria.
    - **Falla de mostradores:** Simula fallas temporales en los puntos de atención.
    - **Botón "REINICIAR SIMULACIÓN":** Vuelve a ejecutar la simulación con los parámetros actuales.

3. **Escenarios predefinidos:**
    - **Normal:** Condiciones típicas.
    - **Estresado:** Mucha demanda y fallas simultáneas.
    - **Colapso:** Situación de desastre.
    - **Valle:** Baja demanda.

4. **Visualiza resultados:**
    - **Gráficos:**  
      - *Calidad de Servicio (Tiempo de Espera y Zonas de Error)*  
      - *Demanda*  
      - *Capacidad*  
      - *Mostradores activos*
    - **Bitácora:** Tabla que muestra eventos importantes y zonas de error detectadas.

---

## ¿Qué parámetros puedo ajustar?

- **Kp:** Ganancia proporcional del controlador.
- **Kd:** Ganancia derivativa.
- **Pico de demanda:** Cantidad máxima de clientes por minuto durante un pico.
- **Inicio de pico:** Momento donde comienza el pico de demanda.
- **Ruido:** Grado de aleatoriedad en la demanda.
- **Falla:** Número de mostradores inhabilitados y momento en que ocurre.

---

## Requisitos

- Sólo necesitas un navegador web moderno (Chrome, Firefox, Edge).
- Conexión a internet para cargar Chart.js vía CDN.

No requiere instalación ni dependencias locales.

---

## ¿Cómo modificar el simulador?

1. Edita el archivo HTML y/o JavaScript.
2. Cambia títulos, lógica, etiquetas, parámetros, etc. según tus necesidades.
3. Si subes cambios a GitHub y tienes Pages habilitado, se verán reflejados automáticamente tras unos minutos.

---

## Créditos

- UTN FRBA, Teoría de Control K-4572

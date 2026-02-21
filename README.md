# Millennium Falcon —
**Scientific Data Validator & Galaxy Dynamics Engine**

## Descripción
Millennium Falcon es una herramienta analítica avanzada ejecutada íntegramente en el navegador. Ha sido diseñada para la validación de curvas de rotación galáctica mediante el procesamiento de datos cinemáticos (Dataset SPARC y Clusters LoCuSS). 

Este dispositivo permite la integración de datos masivos y el ajuste de parámetros de aceleración en tiempo real para evaluar discrepancias en la velocidad de rotación galáctica.

## Capacidades Técnicas
- **Motor V13:** Algoritmo propietario optimizado para el cálculo de aceleración bariónica.
- **Precisión:** Capacidad de reducción del Error Cuadrático Medio (RMS) a niveles de ~3-4 km/s en galaxias de alta resolución como NGC 3198.
- **Integración SPARC:** Procesamiento automático de perfiles de gas, disco y bulbo.
- **Zero Server Footprint:** Privacidad absoluta; todos los cálculos se realizan localmente en el cliente (JavaScript), sin envío de datos a servidores externos.

## Propiedad Intelectual y Derechos
**Copyright © 2026 José Fabián Vallejos. Todos los derechos reservados.**

El código fuente, la lógica de cálculo y los algoritmos contenidos en este repositorio (específicamente la lógica de procesamiento alojada en `app.js`) son propiedad intelectual exclusiva del autor. 

**Queda estrictamente prohibido:**
1. El uso comercial sin autorización expresa.
2. Cualquier intento de ingeniería inversa, desofuscación o copia de las funciones de cálculo maestras.
3. La redistribución del código bajo otros nombres.

Este software se presenta como una prueba de concepto tecnológica para la exploración del cosmos.

## Instrucciones de Uso
1. Clone el repositorio o acceda vía GitHub Pages.
2. Cargue el archivo de datos cinemáticos (formato CSV/ZIP).
3. Ajuste los parámetros de entrada (`tau`, `M/L`) en el panel de control.
4. El sistema generará automáticamente la curva predicha (QUOT) y calculará el RMS.

---
*Hecho en Argentina para la comunidad científica y la exploración del universo.*

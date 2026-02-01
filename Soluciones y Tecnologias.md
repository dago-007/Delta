# Catálogo de Soluciones y Tecnologías: Manufactura de Transformadores

**Descripción:** Listado de proveedores líderes y tecnologías específicas para la implementación de la estrategia 4.0.

---

## 1. Piso de Producción (IIoT y Sensores)
*Para monitorear maquinaria (Bobinadoras, Hornos, Corte).*

### Sensores Industriales (Hardware)
* **IFM Electronic:**
    * *Uso:* Sensores de vibración robustos. Tecnología IO-Link para fácil conexión.
    * *Ventaja:* "Plug-and-play" en motores existentes.
* **Banner Engineering:**
    * *Uso:* Monitoreo de condición inalámbrico (Temperatura + Vibración).
    * *Ventaja:* Ideal para *Retrofit* (máquinas viejas sin cableado nuevo).

### Gestión de Datos (Software/Plataformas)
* **Tulip Interfaces:**
    * *Uso:* Apps "No-Code" para operarios (instrucciones digitales, reportes).
    * *Ventaja:* Muy visual, ideal para sustituir hojas de papel en ensamblaje manual.
* **Siemens (Industrial Edge / MindSphere):**
    * *Uso:* Recolección masiva de datos si ya se usa PLC Siemens.

---

## 2. Ingeniería y Diseño (Gemelos Digitales)
*Para simular estrés térmico y electromagnético.*

* **Ansys Maxwell:**
    * *Categoría:* Estándar de la industria.
    * *Uso:* Simulación precisa de campos electromagnéticos de baja frecuencia.
* **COMSOL Multiphysics:**
    * *Categoría:* Simulación Multifísica.
    * *Uso:* Análisis acoplado de calor (aceite) y electricidad.

---

## 3. Componentes para el "Transformador Inteligente"
*Tecnología para integrar y vender dentro de tu producto final.*

### Monitoreo de Estado (DGA y Aceite)
* **Vaisala:**
    * *Producto:* Serie MHT (Humedad, Hidrógeno y Temperatura).
    * *Ventaja:* Compactos, fiables y fáciles de integrar en el diseño del tanque.
* **Qualitrol:**
    * *Producto:* Monitores completos de salud del transformador, válvulas inteligentes.
    * *Ventaja:* Prestigio de marca y soluciones "todo en uno".

### Control y Cambiadores (Taps)
* **Maschinenfabrik Reinhausen (MR):**
    * *Producto:* ETOS (Embedded Transformer Operating System).
    * *Ventaja:* Sistema abierto para control y monitoreo del cambiador de tomas.

---

## 4. Control de Calidad y Operaciones

### Visión Artificial
* **Cognex:** Cámaras inteligentes para inspección de bobinado (conteo de vueltas, aislamiento).
* **Keyence:** Sensores de medición láser y visión para verificación dimensional de núcleos.

### Realidad Aumentada (Asistencia al Operario)
* **PTC Vuforia:** Software para proyectar instrucciones de ensamblaje (conexionado complejo) sobre la pieza real mediante tablets o gafas AR.

---

## 5. Tabla Comparativa de Implementación

| Área | Solución de Entrada Rápida (Low Barrier) | Solución Corporativa (High End) |
| :--- | :--- | :--- |
| **Diseño** | SolidWorks (Mecánico) | **Ansys Maxwell** (Electromagnético) |
| **Datos Planta** | **Tulip** (Tablets + Apps) | SAP MII / Siemens Opcenter |
| **Sensores Máquina** | **IFM** (Sensores IO-Link) | National Instruments (PXI) |
| **Producto Smart** | **Vaisala** (Sensor simple) | Qualitrol / MR (Sistema DGA completo) |

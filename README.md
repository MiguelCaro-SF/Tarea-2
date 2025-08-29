# Tarea 2 investigación de computadores y oprdenadores
---

## 1. Computación cuántica

La computación cuántica usa principios de la mecánica cuántica —como **superposición**, **entrelazamiento** e **interferencia**— para procesar información.  
A diferencia de la computación clásica (bits 0/1), la unidad básica es el **qubit** que puede existir en combinaciones lineales de 0 y 1 simultáneamente.

### Arquitectura y partes
- **Qubits (procesador cuántico):** superconductores, iones atrapados, fotones, spins, etc.  
- **Control clásico:** electrónica que genera pulsos (microondas, láseres).  
- **Sistema de lectura/medición:** detectores que transforman el estado cuántico en señales clásicas.  
- **Cryogenia/ambiente:** aislamiento extremo o temperaturas ultrabajas.  
- **Software y compiladores cuánticos:** mapean algoritmos a hardware.  
- **Corrección de errores:** redundancia de qubits físicos para qubits lógicos.  

### Historia
- 1980s: Richard Feynman propone simulación cuántica.  
- 1985: David Deutsch formula la máquina cuántica universal.  
- 1994: Peter Shor desarrolla su famoso algoritmo de factorización.  
- 2000s: primeras implementaciones experimentales.  
- 2010s–2020s: plataformas comerciales, supremacía cuántica.  

### Ventajas
- Resolución más rápida de problemas específicos (factorización, búsqueda, simulación).  
- Simulación natural de química y materiales.  

### Desventajas y desafíos
- Coherencia limitada y decoherencia por el ambiente.  
- Elevados errores → necesidad de corrección cuántica.  
- Escalabilidad compleja.  
- No todos los problemas se benefician.  

### Conceptos clave
- **Superposición:** un qubit puede estar en `α|0> + β|1>` con `|α|² + |β|² = 1`.  
- **Entrelazamiento:** correlación cuántica entre qubits, esencial para teleportación.  
- **Interferencia cuántica:** fases se suman/cancelan para reforzar soluciones.  
- **Medición probabilística:** el estado colapsa a 0 o 1 con probabilidades definidas.  
- **Coherencia:** tiempo limitado antes de que se degrade la información.  

### Tipos de comunicación cuántica
- **QKD (distribución de claves cuánticas).**  
- **Teleportación cuántica.**  
- **Superdense coding.**  
- **Redes cuánticas / internet cuántico.**  

### Compuertas cuánticas comunes
- **Un qubit:** Pauli-X, Y, Z, Hadamard (H), Phase (S), T.  
- **Dos qubits:** CNOT, CZ, iSWAP.  
- Combinadas en circuitos para algoritmos.  

---

## 2. Computación neuromórfica

Emula principios del cerebro (redes neuronales y sinapsis) en hardware/software para eficiencia energética y procesamiento paralelo.

### Arquitectura y funcionamiento
- **Neuronas:** integran entradas y generan salidas.  
- **Sinapsis:** pesos de conexión (almacenados localmente o en memristores).  
- **Interconexión:** envío de picos o eventos.  
- **Memoria local y computación en memoria.**  

### Ventajas
- Gran eficiencia energética.  
- Procesamiento masivo en paralelo.  
- Latencia muy baja.  

### Desventajas
- Difícil de programar y entrenar.  
- Ecosistema inmaduro.  
- Precisión limitada en modelos analógicos.  

### Hardware utilizado
- **Digitales especializados:** IBM TrueNorth, Intel Loihi, SpiNNaker.  
- **Analógicos/mixtos:** transistores, capacitores.  
- **Memristores y RRAM:** para pesos en memoria-computación.  

### Tipos
- **Spiking neuromorphic (SNN).**  
- **Rate-based / event-driven.**  
- **Digital neuromorphic.**  
- **Analog / mixed-signal.**  

---

## 3. Ordenador biológico

La computación biológica usa sistemas biológicos o biomoléculas (ADN, ARN, proteínas, células) para procesar información.

### Arquitectura
- **Información:** secuencias de ADN/ARN, estados celulares.  
- **Operadores lógicos:** reacciones químicas, enzimas.  
- **Entradas/salidas:** moléculas o detecciones bioquímicas.  
- **Entorno:** tubos de ensayo, células, microfluidos.  

### Tipos
- **Computación con ADN.**  
- **Computación molecular/enzimática.**  
- **Computación celular/sintética.**  
- **Basada en proteínas.**  

### Principales hitos
- 1994: Leonard Adleman resuelve un problema con ADN.  
- 2000s: puertas lógicas moleculares y circuitos genéticos.  
- 2010s: avances en DNA origami y CRISPR.  
- Actualidad: biocircuitos complejos, biosensores.  

### Ventajas
- Alta densidad de información.  
- Integración en entornos biológicos.  

### Desventajas
- Lento comparado con la electrónica.  
- Protocolos complejos.  
- Desafíos éticos y bioseguridad.  

---

## 4. Computación heterogénea

Combina distintos procesadores (CPU, GPU, FPGA, ASIC) en un sistema para asignar cada tarea a la unidad más eficiente.

### Historia
- Coprocesadores (FPU, DSPs).  
- 2000s: GPUs usadas para cómputo general.  
- 2010s–2020s: aceleradores de IA (TPU, NPU).  

### Ventajas
- Mejor rendimiento por watt.  
- Flexibilidad para cargas diversas.  
- Escalabilidad funcional.  

### Desventajas
- Compleja de programar y optimizar.  
- Problemas de coherencia y latencia.  
- Difícil gestión de recursos.  

---

## 5. Computación de borde (Edge Computing)

Procesa datos cerca de la fuente (IoT, sensores) en lugar de depender solo de la nube.

### Historia
- Surge con IoT y baja latencia (2010s).  
- Evolución a híbrido nube-borde con microcentros de datos.  

### Ventajas
- **Baja latencia:** tiempo real (autos, industria).  
- **Menor ancho de banda:** solo se envía lo esencial.  
- **Privacidad:** datos locales.  
- **Resiliencia:** funciona aun sin nube.  

### Desventajas
- Difícil de gestionar (muchos nodos).  
- Limitación de recursos locales.  
- Riesgo de seguridad distribuida.  

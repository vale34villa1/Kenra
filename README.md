# Kenra - Escudo Digital Antiextorsión
Kenra es un ecosistema de ciberseguridad ciudadana diseñado para proteger a emprendedores, transportistas y MYPES en el Perú frente a la extorsión y el fraude junto a nuestro agente autónomo Qawi.

[![Status](https://img.shields.io/badge/Status-Beta_Launch_March_2026-gold?style=for-the-badge)](#-estado-del-lanzamiento)
[![Architecture](https://img.shields.io/badge/Architecture-Open_Cloud_|_AI_|_Blockchain-blue?style=for-the-badge)](#-arquitectura-tecnológica)
[![Region](https://img.shields.io/badge/Region-Perú-red?style=for-the-badge)](#-cobertura-geográfica)

**Kenra** es un ecosistema de ciberseguridad ciudadana diseñado para proteger a emprendedores, transportistas y MYPES en el Perú frente a la extorsión y el fraude. Transformamos el miedo en evidencia inmutable mediante Inteligencia Artificial y Blockchain.

---

## 🚀 Propuesta de Valor

Eliminamos la fricción de entrada mediante **Qawi**, nuestro agente autónomo. No requiere descarga inicial; el usuario reporta vía WhatsApp, recibe un protocolo de calma y la evidencia es procesada en tiempo real.

### Pilares Tecnológicos:
* 🧠 **Qawi (AI Agent):** Alojado en **Open Cloud**, analiza modalidades (Gota a Gota, Secuestro Virtual) y brinda contención.
* ⛓️ **Blockchain (Polygon):** Sellado de evidencia digital para que sea inmutable y admisible ante la Fiscalía/PNP.
* 🗺️ **Mapa de Inteligencia:** Visualización dinámica de nodos críticos en Lima, Trujillo, Chiclayo y Piura.

---

## 📊 Inteligencia de Datos (Perú 2026)

Basado en el análisis del periodo **16-02-2026 al 18-03-2026**:

| Modalidad de Extorsión | Incidencia (%) |
| :--- | :--- |
| **Amenaza Crimen Organizado** | 35% |
| **Amenaza por Denuncia Falsa** | 5% |
| **Familiar Secuestrado/Aduana** | 7% |
| **Otros (Gota a Gota / Estafas)** | 51% |

> **Nota Técnica:** Los datos son validados mediante un protocolo de consenso en la red **Polygon**, garantizando integridad forense.

---
## 📅 Estado del Lanzamiento
> **Referencia del Badge [Status]**
* **Fase Actual:** Beta Testing (Marzo 2026).
* **Próximo Hito:** Integración de la App móvil para el sellado de evidencia biométrica en Abril 2026.
* **Objetivo:** Desplegar el sistema en los 4 nodos principales del norte peruano antes del Q3.

---

## 🧠 Arquitectura Tecnológica
> **Referencia del Badge [Architecture]**
* **Open Cloud:** Infraestructura distribuida que aloja a **Qawi**, nuestro agente autónomo, garantizando redundancia y rapidez en la respuesta (< 2s).
* **AI Agent (Qawi):** Modelo de lenguaje especializado en detección de patrones de extorsión (Gota a Gota, amenazas directas).
* **Blockchain (Polygon):** Cada reporte genera un hash único en la red Polygon, asegurando que la evidencia sea inalterable para procesos legales.

---

## 📍 Cobertura Geográfica
> **Referencia del Badge [Region]**
* **Lima Metropolitana:** Nodo crítico con mayor volumen de reportes.
* **Trujillo & Chiclayo:** Puntos estratégicos de monitoreo en el sector transporte.
* **Piura (Sullana):** Zona de intervención activa contra el crimen organizado.
* **Validación:** Los datos son alimentados por reportes ciudadanos validados por consenso.

---
## 🛠️ Stack Tecnológico

| Componente | Tecnología |
| :--- | :--- |
| **Frontend** | HTML5, Tailwind CSS, Leaflet.js |
| **IA / Backend** | Agente Autónomo en Open Cloud (Event-Driven) |
| **Web3** | Polygon Labs (Hashing de Evidencia) |
| **Integración** | WhatsApp Business API |

---

## 📁 Estructura del Proyecto

```bash
├── index.html          # Interfaz principal y Mapa de Calor
├── qawi_agent/         # Lógica del Agente Autónomo en la Nube
├── blockchain/         # Smart Contracts para sellado de evidencia
└── docs/               # Requerimientos y Propuesta de Negocio

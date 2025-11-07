
# 🧠 IA Generativa LLM – Sistema Predictivo de Retención "Terrenitos"

## 📌 Descripción
Solución de inteligencia artificial que utiliza **modelos LLM** generativos para analizar conversaciones del call center y datos transaccionales, generando insights predictivos sobre el **comportamiento de clientes** y automatizando estrategias de retención personalizadas basadas en el grado de conformidad y valor del cliente.

## 🎯 Objetivo
Predecir proactivamente el **riesgo de abandono de clientes** mediante el análisis de su grado de conformidad en llamadas, combinado con su historial de pagos, para generar estrategias de retención diferenciadas que optimicen recursos y maximicen la efectividad del equipo de retención.

---

## 🎪 Matriz de Priorización Inteligente

| Grado de Conformidad | Nivel de Facturación | Estrategia | Acciones Específicas |
|---------------------|---------------------|------------|----------------------|
| 🔴 **Bajo** | 🔴 **Bajo** | **Dejar ir** | Si el costo de recuperación es muy elevado |
| 🔴 **Bajo** | 🟢 **Alto** | **Retener** | **💰 Beneficios Económicos** (Prioridad máxima)|
| 🟢 **Alto** | 🔴 **Bajo** | **Cuidar** | **🎁 Programas de fidelización** |
| 🟢 **Alto** | 🟢 **Alto** | **Monitorear** | **🛡️ Preventivo proactivo** |

---

## 📊 Fuentes de Datos
### 🔹 Datos No Estructurados
- Llamadas del Call Center a clientes

- Grabaciones almacenadas en servidor externo

### 🔹 Datos Estructurados
- Base de Datos de clientes

- Base de Datos de pagos
  
- Base de Datos de facturación

---

## ⚙️ Solución

Se utiliza un modelo **OpenAI LLM** con **embeddings en Python** para evaluar el tono y la conformidad en las conversaciones.
Los resultados se integran con la información de pagos y facturación para generar una Matriz de Priorización de Clientes que guía las acciones del equipo de retención.

---
## 🧩 Flujo General

```bash
CRM (llamadas) + ERP (pagos)
        ↓
Embeddings OpenAI → Grado de conformidad
        ↓
Matriz de priorización de clientes
```

## 📦 Requisitos

- Python 3.8 o superior
- Una clave de API de OpenAI (`OPENAI_API_KEY`)
- Conexión a internet

---

## 🛠️ Instalación y ejecución local

### 1. Clona el repositorio Y crear entorno

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio

pip install -r requirements.txt
```
## 🎉 Resultado

<img width="900" height="1035" alt="Image" src="https://github.com/user-attachments/assets/3e2b7c36-50db-4fda-a473-7e8d8dd31086" />

<img width="850" height="1038" alt="Image" src="https://github.com/user-attachments/assets/05140db1-e6ef-4656-9cf9-970325fae0c3" />

## ✅ Beneficios Directos

🔍 Mejora la comprensión del cliente mediante análisis de sentimientos

🧠 Automatiza el análisis de satisfacción en tiempo real

📈 Optimiza la retención con decisiones basadas en datos

🎯 Priorización inteligente de esfuerzos comerciales


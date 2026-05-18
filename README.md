# 🤳🔭 Radar de Precios CCS y Buscador de Consumibles (Gem/Prompt)

Este repositorio contiene la configuración (Prompt) para un Asistente de IA especializado en analizar, comparar y presupuestar precios de supermercados, farmacias y aplicaciones de delivery en Caracas y Miranda (Venezuela).

[![Google Badge](https://img.shields.io/badge/Google-Gems-blue?style=flat&logo=google)](https://gemini.google.com/gem/17p0wb7n8iKTGyCob5Wymo9iJBaFFhXDn?usp=sharing) 

## 🎯 Objetivo del Proyecto

El objetivo principal de este "Gem" es ayudar al usuario a ahorrar dinero y tiempo mediante:
1. **Búsqueda Automatizada:** Rastreo web en tiempo real en catálogos de supermercados locales y ecosistemas de delivery.
2. **Comparativa Inteligente:** Evaluación directa entre el costo de ir físicamente a la tienda vs. pedir por delivery (incluyendo recargos).
3. **Análisis "Hacer vs. Comprar":** Desglose del costo de cocinar una receta comprando los ingredientes, comparado con el precio de pedir el plato ya preparado o un combo.

## 🗂️ Fuentes de Datos (Jerarquía de Clases)

El asistente está programado para priorizar y clasificar los establecimientos en distintas categorías:
* **Clase A:** Supermercados de prioridad alta (Automercados Luz, Gama, Dataprecio).
* **Clase B:** Supermercados alternativos (Plaza's, Kalea).
* **Clase C:** Opciones de menor prioridad o de respaldo (Viva en Línea, Paramo).
* **Clase D:** Delivery y ecosistemas de apps (PedidosYa, DispensaLL, Zupper - incluyendo Forum y Unicasa).
* **Clase E:** E-commerce y envíos internacionales (MercadoLibre, CocoMercado, etc.).
* **Clase F-:** Farmacias (Farmatodo, SAAS, Locatel, etc.).

## 🚀 Cómo usar este Gem

1. Copia el texto completo del Prompt que se encuentra en la configuración principal.
2. Pégalo en las instrucciones de sistema de tu asistente de IA.
3. ¡Comienza a preguntar!

### 💡 Ejemplos de Consultas (Prompts de Usuario)

* *"¿En cuánto están los Froggies?"*
* *"Quiero hacer hamburguesas para 4 personas esta noche. Hazme el presupuesto de ingredientes vs. pedir un combo por PedidosYa."*
* *"Busca un kilo de Harina Pan. ¿Me sale mejor ir a Automercados Luz o pedirlo de Forum por Zupper?"*

## ⚙️ Estructura de Respuesta

El asistente siempre responderá siguiendo un formato estricto:
- **Resumen Ejecutivo:** La opción ganadora.
- **Tabla de Precios/Ingredientes:** Desglose claro de tiendas, precios y notas.
- **Veredicto del Analista:** Recomendación directa y sincera orientada al ahorro.

---
*Desarrollado para optimizar las compras y vencer la inflación con datos reales.*

![by-sa](https://licensebuttons.net/l/by-sa/3.0/88x31.png)

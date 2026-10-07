# 🛢️ Sistema B2B — Grupo Líder 360 C.A.

> **Sistema B2B (Business-to-Business) para la Gestión Integral de Pedidos al Mayor**  
> Proyecto de Grado para optar al título de Ingeniero de Sistemas — *Instituto Universitario Politécnico "Santiago Mariño" (Ampliación Mérida)*.

---

## 📌 Descripción General

Este proyecto consiste en una plataforma web transaccional **B2B (Business-to-Business)** desarrollada para optimizar, centralizar y automatizar el ciclo integral de pedidos al mayor en la empresa **Grupo Líder 360 C.A.**, distribuidora mayorista de lubricantes automotrices e industriales.

El sistema reemplaza flujos operativos informales y descentralizados (hojas de cálculo, mensajería de WhatsApp y llamadas) por un entorno digital unificado, mitigando errores humanos, eliminando duplicidad de datos y agilizando la relación comercial con distribuidores y clientes corporativos.

---

## 🚀 Características y Módulos Principales

### 1. 🔐 Autenticación y Control de Acceso por Roles (RBAC)
- Inicio de sesión seguro con contraseñas encriptadas.
- Vistas, permisos y paneles adaptados por perfil: **Administrador / Gerente de Ventas**, **Personal Administrativo** y **Distribuidor Autorizado**.

### 2. 📦 Catálogo Interactivo y Verificación de Stock en Tiempo Real
- Visualización dinámica del catálogo de productos con fichas técnicas por marca, viscosidad y presentación.
- Filtros por marcas (Shell, Pennzoil, Mobil, etc.) y motor de búsqueda predictivo.
- Validación automática de existencias en base de datos para prevenir preventas sin inventario físico.

### 3. 🛒 Gestión de Pedidos y Escalas de Precios
- Carrito de compras con cálculo automático de subtotales y aplicación algorítmica de descuentos por volumen de compra.
- Registro transaccional de órdenes con código único y seguimiento de estatus (*Pendiente por Procesar*, *Aprobado*, *En Almacén*, *Despachado*).
- Generación de cotizaciones mayoristas (*Wholesale*) y emisión de comprobantes digitales descargables.

### 4. 📊 Gestión de Inventario y Auditoría
- Panel tabular interactivo para monitoreo y actualización rápida de existencias.
- Registro y catalogación de nuevos artículos (SKUs).
- Sistema de alertas visuales automáticas ante niveles de stock crítico o riesgo de ruptura de inventario.

### 5. 🚚 Trazabilidad Logística y Despachos
- Módulo de seguimiento en tiempo real con línea de tiempo del despacho.
- Asignación de unidades de transporte, registro de rutas y puntos de control.
- Integración visual para monitoreo y confirmación de entrega en destino.

### 6. 💼 Gestión de Cartera, Créditos y Mensajería
- Control de solvencia, límites de crédito comercial y auditoría de saldos pendientes por distribuidor.
- Canal de comunicación y mensajería interna centralizado por transacción con soporte para adjuntar archivos digitales.
- *Dashboard* gerencial con KPIs de ventas mensuales, saldos y rotación de productos.

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** & **CSS3**
- **JavaScript / TypeScript**
- **React** (empaquetado y servido con **Vite**)
- **Bootstrap** (diseño adaptativo y responsivo multidispositivo)

### Backend
- **Python 3.x**
- **Django** & **Django REST Framework (DRF)** (arquitectura de APIs RESTful desacoplada)

### Base de Datos & Almacenamiento
- **PostgreSQL** (base de datos relacional normalizada en 3FN)

### Metodología de Desarrollo
- **Extreme Programming (XP)** (iteraciones cortas, retroalimentación continua, programación modular y pruebas unitarias/funcionales).

---

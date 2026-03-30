# SUMMA Industrial Supplies - Business Intelligence Dashboard

[English Version](#english-version) | [Versión en Español](#spanish-version)

<a name="english-version"></a>
## English Version

This repository contains an advanced Business Intelligence (BI) platform and an Executive Dashboard designed for SUMMA, an industrial supplies company. The project integrates real-time data visualization, predictive analytics, and an Artificial Intelligence assistant.

[View Live Demo (Vercel)](#)

---

### Project Structure
The repository is organized for easy navigation and maintenance:
- **web/**: Dashboard interface and interactive web applications.
- **src/** (Ignored): Python core logic for data processing, cleaning, and integration.
- **data/** (Ignored): Datasets (CSV, XLSX) and samples for analysis.
- **docs/** (Ignored): Technical documentation and analytical models.

---

### Key Features
- **1. Dynamic Executive Panel:** Commercial KPIs including Total Sales, YoY Variation, and Weekly Projections.
- **2. RFM Customer Segmentation:** Automatic classification into Champions, Loyal, At Risk, and Hibernating categories.
- **3. AI (SUMMA-Bot):** Virtual assistant using Google Gemini 1.5 Flash for real-time business insights.
- **4. Predictive Models:** Demand forecasting with 95% confidence intervals and seasonal pattern detection.
- **5. Inventory Control:** Monitoring for Slow Movers and customer dependency analysis (Whale Risk).

---

### Technologies
- **Frontend:** HTML5, CSS3 (Glassmorphism design), JavaScript (ES6+).
- **Visualization:** Chart.js and D3.js.
- **Data Backend:** Python 3.x (Pandas, Numpy, Scikit-learn).
- **Database:** Supabase (PostgreSQL).
- **Artificial Intelligence:** Google Gemini API.

---

### Getting Started

#### Guest Access (Demo Mode)
- **User:** invitado / **Password:** Invitado123
- The system automatically loads a local test dataset for exploration.

#### Data Structure Requirements
If you upload your own CSV, the system is flexible with column names:

| Field | Accepted Variation Names |
| :--- | :--- |
| **Customer** | customer, cliente, nombre_cliente, razon_social |
| **Product** | product, producto, nombre_producto |
| **Group** | category, grupo, grupo_inventario |
| **Value** | gross_value, valor_bruto, valor |
| **Quantity** | qty, cantidad, cantidad_vendida |
| **Month** | month, mes (Number or month name) |
| **Year** | year, anio, año |
| **Discount** | discount, descuento (Optional) |

#### Installation
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Tomate32/Pag-Sum.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Setup environment:**
    - Configure .env based on .env.example with your Supabase credentials.

---

<br/>
<a name="spanish-version"></a>

## Versión en Español

Plataforma avanzada de Business Intelligence (BI) y Dashboard Ejecutivo para la empresa SUMMA. Visualización interactiva, análisis de datos predictivo y asistente impulsado por IA.

---

### Estructura del Proyecto
- **web/**: Interfaz del dashboard y aplicaciones web interactivas.
- **src/** (Ignorado): Lógica central en Python para procesamiento de datos.
- **data/** (Ignorado): Conjuntos de datos (CSV, XLSX) para análisis.
- **docs/** (Ignorado): Documentación técnica y explicaciones de modelos analíticos.

---

### Características Principales
- **1. Panel Ejecutivo:** KPIs comerciales: Ventas totales, Variación YoY y Proyecciones semanales.
- **2. Segmentación RFM:** Clasificación automática de clientes según Recencia, Frecuencia y Valor.
- **3. Inteligencia Artificial (IA):** Asistente basado en Google Gemini 1.5 Flash con contexto de negocio.
- **4. Análisis Predictivo:** Predicción de demanda basada en estacionalidad e históricos de ventas.
- **5. Monitoreo de Inventario:** Detección de productos de baja rotación (Slow Movers) y riesgos financieros.

---

### Tecnologías Utilizadas
- **Frontend:** HTML5, CSS3 (Diseño Glassmorphism), JavaScript (ES6+).
- **Visualización:** Chart.js y D3.js.
- **Backend:** Python 3.x (Pandas, Numpy, Scikit-learn).
- **Base de Datos:** Supabase.
- **IA:** Google Gemini API.

---

### Cómo Empezar

#### Acceso para Invitados (Modo Demo)
- **Usuario:** invitado / **Contraseña:** Invitado123
- Carga automática de datos de prueba locales para navegación libre.

#### Estructura de Datos (CSV)
El sistema es flexible con los nombres de las columnas:

| Campo | Nombres aceptados (Variaciones) |
| :--- | :--- |
| **Cliente** | cliente, customer, nombre_cliente, razon_social |
| **Producto** | producto, product, nombre_producto |
| **Grupo** | grupo, category, grupo_inventario |
| **Valor** | valor_bruto, gross_value, valor |
| **Cantidad** | cantidad, qty, cantidad_vendida |
| **Mes** | mes, month (Número o nombre del mes) |
| **Año** | anio, año, year |
| **Descuento** | descuento, discount (Opcional) |

#### Instalación
1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/Tomate32/Pag-Sum.git
    ```
2.  **Instala dependencias:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Configuración del entorno:**
    - Configura tu archivo .env basándote en .env.example con tus credenciales de Supabase.

---

### Impacto del Negocio
- Identificación de fugas por descuentos y anticipación de la demanda de productos clave.
- Reactivación de clientes en riesgo antes de la pérdida de actividad permanente.

---

## Author
**Tomate32** - Data Solutions & Business Intelligence Developer.

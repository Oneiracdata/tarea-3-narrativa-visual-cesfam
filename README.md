# Tarea 3: Narrativa Visual con Datos - CESFAM

## 📊 Descripcion General

Este proyecto desarrolla una **narrativa visual completa** utilizando un conjunto de 22,235 registros de atenciones de salud familiar en un CESFAM (Centro de Salud Familiar) durante el periodo julio-diciembre 2025.

### Objetivo Principal
Transformar un análisis de datos en una **historia clara, memorable y accionable** utilizando el framework narrativo **Setup-Insight-Implicacion**.

---

## 📐 Framework Narrativo: Setup-Insight-Implicacion

### 1. SETUP (Contexto del Problema)
Establece el panorama general sin interpretaciones controvertibles:
- Volumen y distribución de atenciones
- Top especialidades y profesionales
- Periodicidad temporal de datos

### 2. INSIGHT (Hallazgos Clave)
Revela patrones y anomalías que importan:
- 80.5% tasa de confirmación de citas vs 15% sin respuesta
- Concentración: 4 especialidades con 60% de atenciones
- Desigualdad: 3.3x diferencia de carga entre profesionales
- Patrón semanal: Picos martes-miércoles

### 3. IMPLICACION (Acción Requerida)
Convierte datos en recomendaciones accionables:
- Automatizar confirmación de citas (Alto impacto, Bajo esfuerzo)
- Rebalancear carga de trabajo entre profesionales
- Optimizar horarios según demanda real

---

## 📁 Estructura del Repositorio

```
tarea-3-narrativa-visual-cesfam/
├── README.md                      # Esta documentacion
├── data/
│   ├── board.csv                  # Dataset original (22,235 registros)
│   └── data_processed.csv         # Datos procesados para analisis
├── notebooks/
│   ├── analisis_cesfam.ipynb     # Notebook Colab con codigo
│   └── exploratory_data_analysis.py
├── figures/
│   ├── grafico_1_serie_tiempo.png
│   ├── grafico_2_especialidades.png
│   ├── grafico_3_profesionales.png
│   └── visualizaciones_adicionales/
├── ppt/
│   └── CESFAM_Narrativa_Visual.pptx
└── requirements.txt               # Dependencias Python
```

---

## 🔍 Hallazgos Principales

| Metrica | Valor | Insight |
|---------|-------|----------|
| **Total de atenciones** | 22,235 | Periodo: Jul-Dic 2025 |
| **Promedio mensual** | ~3,700 | Volumen estable sin anomalias |
| **Top especialidad** | Enfermeria | 25-30% del total |
| **Tasa confirmacion** | 80.5% | Gap: 15% sin respuesta |
| **Concentracion** | 4 especialidades | 60% de todas atenciones |
| **Desigualdad laboral** | Ratio 3.3x | Oportunidad: Rebalancear |
| **Demanda pico** | Mar-Mie | 30-35% de citas semanales |

---

## 🛠️ Herramientas Utilizadas

### Analisis de Datos
- **Python 3.9+**
- **Pandas** - Manipulacion y limpieza de datos
- **NumPy** - Operaciones numericas
- **Google Colab** - Entorno de ejecucion

### Visualizacion
- **Matplotlib** - Graficos base
- **Seaborn** - Estilos y temas visuales
- **Google Sheets** - Exploracion inicial

### Presentacion
- **Google Slides** - Presentacion narrativa
- **PowerPoint** - Formato final

### Documentacion
- **GitHub** - Control de versiones
- **Google Docs** - Planificacion del proyecto
- **Markdown** - Documentacion

---

## 📋 Requisitos para Reproducir

```bash
# Instalar dependencias
pip install -r requirements.txt

# O manualmente:
pip install pandas numpy matplotlib seaborn
```

### Para ejecutar el analisis:
1. Abrir Google Colab
2. Cargar notebook: `notebooks/analisis_cesfam.ipynb`
3. Ejecutar celdas en orden
4. Los graficos se generaran en `/figures/`

---

## 📊 Visualizaciones Principales

### Grafico 1: Serie de Tiempo (SETUP)
**Titulo Activo:** "Las atenciones de salud familiar se estabilizan en ~3,700 citas mensuales"
- Linea temporal de julio a diciembre 2025
- Muestra estabilidad sin picos anomalos

### Grafico 2: Top Especialidades (SETUP)
**Titulo Activo:** "Enfermeria y Medicina concentran el 45% de todas las atenciones"
- Barras horizontales ordenadas
- Top 10 especialidades destacadas

### Grafico 3: Top Profesionales (SETUP)
**Titulo Activo:** "Natalia Diaz y 4 colegas realizan el 25% de todas las atenciones"
- Barras con color diferenciado (top 5 vs resto)
- Evidencia de desigualdad de carga

---

## 💡 Recomendaciones Accionables

### Corto Plazo (0-3 meses)
- **Iniciativa:** Automatizar confirmacion SMS/WhatsApp
- **Impacto:** Reducir no-respuesta del 15% al 8% (1,100+ citas confirmadas)
- **Esfuerzo:** Bajo - ROI inmediato

### Mediano Plazo (3-6 meses)
- **Iniciativa:** Rebalancear carga entre profesionales
- **Impacto:** Mejorar eficiencia 15-20%, reducir tiempo de espera
- **Esfuerzo:** Medio

### Largo Plazo (6-12 meses)
- **Iniciativa:** Optimizar horarios segun demanda real
- **Impacto:** Escalar a 25,000+ atenciones anuales
- **Esfuerzo:** Alto pero transformador

---

## 📚 Referencias y Fuentes

### Dataset
- **Nombre:** board.csv (Google Sheets)
- **Periodo:** Julio - Diciembre 2025
- **Registros:** 22,235
- **Acceso:** https://docs.google.com/spreadsheets/d/18NCnPsq1qUr4kUemGDb-BJHFy5qiUDc6qZ4OYAx78LQ/

### Frameworks de Storytelling
- Cole Nussbaumer Knaflic - "Storytelling with Data"
- Nancy Duarte - "Resonate"
- Sinek, Simon - "Start with Why"

### Herramientas AI Utilizadas
- **Claude (Anthropic)** - Asistencia en estructura narrativa
- **Comet (Perplexity)** - Asistencia en automatizacion y documentacion

---

## 👨‍💻 Autor

**Osvaldo Antonio Neira Castillo**
- Estudiante: Programa Data Science, Universidad del Desarrollo (UDD)
- Email: osvaldoneira@gmail.com
- GitHub: [@Oneiracdata](https://github.com/Oneiracdata)

---

## 📅 Fecha de Entrega

**10 de Diciembre de 2025, 23:59 hrs**

---

## 📝 Licencia

Este proyecto es de caracter academico bajo la licencia MIT.

---

## 🚀 Estado del Proyecto

✅ Analisis completado
✅ Visualizaciones generadas
✅ Presentacion estructurada
✅ Documentacion completa
✅ Repositorio GitHub activo

**Proyecto ENTREGADO Y FUNCIONAL**

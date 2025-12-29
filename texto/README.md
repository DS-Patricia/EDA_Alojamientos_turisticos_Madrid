
# 🏨 EDA Alojamiento Turístico en Madrid  
### *Análisis Exploratorio de Datos con Inside Airbnb*

---

## 📌 Descripción breve  
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre los alojamientos turísticos de Madrid utilizando el dataset público de Inside Airbnb. El objetivo es comprender cómo se distribuye la oferta dentro de la ciudad, cómo varían los precios y qué factores parecen influir en dichas variaciones.

---

## 🔍 Hipótesis planteada  
La hipótesis principal del proyecto es:

> **Las diferencias de precio entre los alojamientos turísticos en Madrid pueden explicarse principalmente por la ubicación, el tipo de alojamiento, las características del anuncio y la época del año.**

**Las diferencias de valoraciones y frecuencia de uso de los pisos turísticos pueden explicarse principalmente por el precio, la ubicación, el tipo de alojamiento, las características del anuncio y la época del año**

Preguntas adicionales:  
- ¿Qué barrios concentran más oferta de alojamientos?  x
- ¿Qué zonas presentan los precios más altos?  x
- ¿Existen diferencias entre anfitriones particulares y multi-hosts? x 

- ¿Existen zonas desaprovechadas (zonas con muy poca densidad de oferta pero mucho índice de beneficio)?
- ¿Existen zonas sobreexplotadas (zonas con muy mucha densidad de oferta pero poco índice de beneficio)?
- ¿Las características de los pisos turísticos con más éxito varían en base a la ubicación u otros factores relacionados?
- ¿Son los pisos turísticos con precios más altos los que reportan mayores beneficios?

---

## 🛠️ Tecnologías utilizadas  
- Python 3.10+  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- ReportLab (para generación de PDF, si aplica)

---

## 📁 Estructura del repositorio  

```
📦 EDA-Alojamiento-Turístico-Madrid
│
├── README.md                → Documento principal del proyecto
├── main.ipynb               → Notebook final y limpio con el EDA completo
├── Memoria.pdf              → Documento técnico extendido del análisis
├── Presentacion.pdf         → Diapositivas utilizadas para la exposición
│
└── src/                     → Código auxiliar del proyecto
     ├── limpieza.py         → Funciones de limpieza y transformación
     ├── visualizaciones.py  → Funciones para generar gráficos
     └── utils.py            → Funciones adicionales de soporte
```

---

## ▶️ Instrucciones de reproducción  

### 1. Clonar el repositorio  
```
git clone https://github.com/usuario/EDA-Alojamiento-Madrid.git
cd EDA-Alojamiento-Madrid
```

### 2. Crear entorno e instalar dependencias  
```
pip install -r requirements.txt
```

### 3. Abrir el notebook  
```
jupyter notebook main.ipynb
```

### 4. Ejecutar el análisis  
Seguir las celdas del notebook en orden:  
- Carga del dataset  
- Limpieza y preprocesado  
- Visualizaciones  
- Conclusiones  

---

## 📊 Principales conclusiones  
- La ubicación es el factor que más influye en el precio del alojamiento.  
- Los barrios céntricos concentran la mayor oferta y muestran precios más altos.  
- Los alojamientos completos son significativamente más caros que las habitaciones privadas.  
- Los multi-hosts representan una parte importante del mercado en zonas de alta demanda.  
- La disponibilidad y el número de reseñas también muestran patrones relevantes.

---

## 👥 Autores  
- **Patricia García Rabasco**  
- **Javier López Cervino**  
- **Pilar Gutiérrez Giménez**

---


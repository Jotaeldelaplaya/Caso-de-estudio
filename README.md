# Caso-de-estudio
Se realizo este caso de estudio para poner en practica los conocimientos adquiridos enmi crtificado profesional Google Data Analyst
# 📊 Análisis de Datos: Estudio de Caso Bellabeat  

## 📝 Introducción  
Este estudio de caso analiza datos de dispositivos inteligentes para identificar tendencias en el uso de wearables de salud. Bellabeat, una empresa de tecnología enfocada en el bienestar de la mujer, busca mejorar su estrategia de marketing basándose en estos hallazgos.  

## 🎯 Objetivos  
- Identificar **tendencias en el uso de dispositivos inteligentes**.  
- Aplicar estos hallazgos a **un producto de Bellabeat**.  
- Proporcionar **recomendaciones estratégicas** basadas en datos.  

## 📂 Fuentes de Datos  
Utilizamos el conjunto de datos público **Fitbit Fitness Tracker Data**, disponible en [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit). Este dataset incluye información de 30 usuarios sobre:  
- **Actividad física diaria**: Pasos, calorías, minutos activos y sedentarios.  
- **Frecuencia cardíaca**: Registros a nivel de segundos.  
- **Sueño**: Horas dormidas, calidad del sueño.  
- **Peso y composición corporal**: Peso en kg, IMC, grasa corporal.  

📌 **Limitaciones del dataset**:  
- Solo **30 participantes**, lo que limita la generalización de los resultados.  
- Falta de datos demográficos que podrían influir en los patrones analizados.  

## 🛠 Proceso de Análisis  
### 🔹 Limpieza de Datos  
- Eliminamos registros duplicados en los datos de sueño.  
- Convertimos las fechas al formato adecuado (`datetime`).  
- Eliminamos valores nulos en la variable `Fat` (grasa corporal).  

### 🔹 Análisis Exploratorio  
1. **Promedio de Pasos por Día**:  
   - Los usuarios caminan **7,638 pasos/día en promedio**.  
   - La mayoría no alcanza los **10,000 pasos diarios** recomendados.  
   - 🔍 *Posible acción*: Bellabeat podría incentivar retos de pasos en su aplicación.  

2. **Minutos Activos vs. Sedentarios**:  
   - **Minutos activos promedio**: **228 min/día (~3.8 horas)**.  
   - **Minutos sedentarios promedio**: **991 min/día (~16.5 horas)**.  
   - 🔍 *Posible acción*: Implementar notificaciones en la app para reducir el tiempo sedentario.  

3. **Distribución del Sueño**:  
   - **Promedio de sueño por noche**: **6.99 horas**.  
   - Muchos usuarios duermen **menos de 7 horas**, por debajo del estándar recomendado.  
   - 🔍 *Posible acción*: Crear contenido educativo sobre la importancia del descanso en la app.  

4. **Relación entre Actividad Física y Sueño**:  
   - No encontramos **correlaciones fuertes** entre minutos activos y calidad del sueño.  
   - 🔍 *Posible acción*: Bellabeat podría agregar funciones en su app para evaluar cómo el ejercicio afecta el descanso.  

## 📢 Recomendaciones para Bellabeat  
📌 Basado en el análisis, sugerimos:  
✅ **Fomentar más actividad física** mediante retos, notificaciones y recompensas en la app.  
✅ **Reducir el tiempo sedentario** con recordatorios y contenido educativo.  
✅ **Mejorar la calidad del sueño** a través de herramientas de seguimiento avanzadas.  
✅ **Explorar nuevas fuentes de datos** para obtener información más detallada sobre usuarias.  

## 📌 Conclusión  
Este análisis proporciona información valiosa para mejorar la estrategia de marketing de Bellabeat. A pesar de las limitaciones del dataset, los hallazgos sugieren oportunidades clave para aumentar la participación de los usuarios y mejorar la experiencia de los productos de Bellabeat.  

🚀 **Próximos pasos**:  
- Ampliar la muestra de datos para hacer análisis más precisos.  
- Implementar pruebas A/B con estrategias basadas en los insights obtenidos.  
- Integrar estos resultados en futuras campañas de marketing digital.  

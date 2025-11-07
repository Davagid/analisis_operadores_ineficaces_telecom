# Identificar operadores ineficaces — CallMeMaybe

## Descripción
Análisis de datos para identificar operadores ineficaces en la plataforma CallMeMaybe, usando métricas de llamadas (llamadas perdidas, tiempo de espera, proporción inbound/outbound e internas). Incluye EDA, pruebas estadísticas y un sistema de scoring multidimensional.

## Objetivos
- Analizar patrones de eficiencia/ineficiencia entre operadores.
- Definir criterios cuantitativos para clasificar operadores.
- Entregar conclusiones y recomendaciones accionables para supervisores.

## Tecnologías y librerías
- Python (pandas, numpy, matplotlib, seaborn, scipy, scikit-learn).
- Jupyter Notebook (análisis reproducible).

## Conclusiones
- Se identificaron **113 operadores ineficaces** (10.4% del total) mediante un sistema de scoring multidimensional validado estadísticamente.  
- Los operadores ineficaces presentan **tiempos de espera excesivos**, **mayor volumen de llamadas perdidas** y **baja colaboración interna**.  
- Las pruebas estadísticas confirmaron diferencias altamente significativas entre operadores eficientes e ineficientes (p-value < 0.0001).  
- Se comprobó que la **eficiencia no puede evaluarse con métricas aisladas**, sino a través de un enfoque multidimensional.  
- Las recomendaciones incluyen **reentrenamiento focalizado**, **balance de cargas operativas** y la implementación de un **dashboard en tiempo real** para monitoreo continuo.

## Instrucciones de uso
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/analisis_operadores_ineficientes.git
   cd analisis_operadores_ineficientes
2. Instalar las dependencias:

    pip install -r requirements.txt

3. Abrir el notebook principal:

    notebooks/analisis_operadores_ineficientes.ipynb

4. Ejecutar las celdas para reproducir el análisis y los resultados.

> Nota: las versiones y dependencias exactas sen encuentran en: `requirements.txt`.
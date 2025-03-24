# Plantix: IA en Agricultura  

## Descripción  
Aplicación móvil que identifica enfermedades en plantas mediante fotos.  

## Características Cumplidas  
- **Percepción**: Analiza imágenes de hojas o frutos para detectar patologías.  
- **Aprendizaje**: Mejora su precisión con cada imagen subida por usuarios.  
- **Orientación a objetivos**: Provee soluciones inmediatas (ej: pesticidas recomendados).  

## Limitaciones  
- **Autonomía**: Requiere confirmación humana para diagnósticos complejos.  
- **Razonamiento**: No sugiere tratamientos personalizados según el tipo de suelo o clima.  

## Aspectos Éticos  
- **Transparencia**: Explica cómo llegó al diagnóstico (pero no comparte el modelo interno).  
- **Privacidad**: Las imágenes de cultivos se almacenan de forma anónima.  

## Funcionamiento Técnico (Hipótesis)  
1. **Redes Neuronales Convolucionales (CNN)**: Clasifica imágenes comparándolas con una base de datos de enfermedades.  
2. **Procesamiento en la nube**: Las fotos se envían a servidores para análisis detallado.  
3. **Feedback loop**: Los agricultores confirman diagnósticos, retroalimentando el modelo.  

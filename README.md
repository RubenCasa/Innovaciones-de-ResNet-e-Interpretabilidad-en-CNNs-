 Estudio de Caso: Innovaciones de ResNet e Interpretabilidad en CNNs 🧠🤖

¡Bienvenido al repositorio del estudio de caso sobre **Redes Neuronales Residuales (ResNet)**! Este proyecto analiza las principales innovaciones arquitectónicas que permitieron entrenar redes neuronales extremadamente profundas y explora cómo visualizar e interpretar estas "cajas negras".

##  Contenido del Proyecto

Este repositorio incluye explicaciones teóricas. Los temas principales son:

1. **La Súper Carretera de los Gradientes**: Explicación del problema del gradiente desvanecido y cómo las *skip connections* (conexiones de salto) de ResNet lo solucionan.
2. **Eficiencia con Convoluciones Bottleneck**: Cómo reducir y expandir dimensionalidades con convoluciones 1x1 y 3x3 para ahorrar poder computacional.
3. **Mapas de Saliencia**: Técnicas de visualización basadas en gradiente para saber exactamente en qué píxeles se concentra la red neuronal al tomar una decisión.
4. **Convergencia Interdisciplinaria**: El paralelismo matemático entre la arquitectura de las CNNs y el funcionamiento biológico de la corteza visual humana.


## 🚀 Cómo ejecutarlo

Si deseas correr el cuaderno interactivamente:

1. Asegúrate de tener Python y Jupyter instalados.
2. Instala las dependencias necesarias:
   ```bash
   pip install torch matplotlib jupyter
   ```
3. Inicia Jupyter Notebook en tu terminal:
   ```bash
   jupyter notebook
   ```
4. Abre `estudio_de_caso_resnet.ipynb` y ejecuta las celdas.

##  Referencias

* He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep Residual Learning for Image Recognition. *CVPR*.
* Simonyan, K., Vedaldi, A., & Zisserman, A. (2014). Deep Inside Convolutional Networks. *ICLR Workshop*.

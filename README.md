# 🚜 Predicción del Precio de Venta de Excavadoras

## 📌 Descripción

Este proyecto aplica técnicas de aprendizaje automático para predecir el precio de venta de excavadoras utilizando datos históricos y características relevantes. 

## 🛠 Tecnologías Utilizadas

- **Python** como lenguaje principal.
- **Pandas y NumPy** para manipulación de datos.
- **Scikit-Learn** para el entrenamiento de modelos.
- **Matplotlib y Seaborn** para visualización de datos.
- **Jupyter Notebook** para desarrollo y experimentación.

## 📊 Resultados

### Modelo Ideal (`ideal_model`)
- **Training R²:** 0.96
- **Validation R²:** 0.88
- **Training MAE:** 2953.82
- **Validation MAE:** 5951.25

## 📈 Evaluación del Modelo

- Buen desempeño en entrenamiento (R² = 0.96) y validación (R² = 0.88)
- La diferencia entre Training MAE y Valid MAE sugiere que el modelo puede estar ajustado adecuadamente.

## 🔧 Posibles Mejoras

1. Probar modelos más avanzados como Gradient Boosting (XGBoost, LightGBM o CatBoost)
2. Ajustar hiperparámetros mediante Grid Search o Bayesian Optimization para mejorar el rendimiento.
3. Implementar técnicas de validación cruzada para reducir el riesgo de sobreajuste.

## 🏁 Conclusión

El modelo desarrollado logra una predicción razonablemente precisa del precio de venta de excavadoras, con un rendimiento satisfactorio en el conjunto de validación. 
Sin embargo, existen oportunidades de mejora a través de técnicas avanzadas de modelado y enriquecimiento de datos.


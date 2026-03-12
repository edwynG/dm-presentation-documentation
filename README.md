# Predicción de popularidad en Spotify
Usando el dataset ``data/spotify_tracks.csv``, creamos un notebook donde hicimos todo el proceso de minería de datos. El objetivo fue ver si es posible predecir la posición de una canción en el ranking de Spotify basándonos en sus características técnicas como el tempo, la energía, lo bailable que es y en el significado de su contenido. A partir de este análisis, preparamos la presentación.

### Contenido requerido:
- Selección justificada de metodología y la documentación de su uso.
- Aplicación de técnicas de preprocesamiento de datos.
- Análisis exploratorio de los datos.
- Al menos un caso de uso de algoritmos predictivos o descriptivos.

# Resumen de la presentación
Usamos la metodología **CRISP-DM** porque es un estándar que ayuda a conectar bien los objetivos del negocio con el análisis técnico. El objetivo principal fue reducir riesgos al invertir en marketing musical, trabajando con un conjunto de datos de 114,000 canciones de Spotify. Primero limpiamos y preparamos los datos, eliminando valores faltantes, columnas irrelevantes y datos extremos para asegurar calidad y evitar errores en el modelo.
Al analizar los datos, vimos que la popularidad está muy concentrada en pocas canciones exitosas. Descubrimos que la bailabilidad es la característica que más influye en el éxito, mientras que las canciones muy instrumentales suelen ser menos populares. Además, la gente prefiere música con mucha energía. Para entender mejor los títulos de las canciones, usamos técnicas de procesamiento de lenguaje natural que convierten los nombres en vectores y miden qué tan relacionados están con temas como amor, fiesta y tristeza. Sin embargo, al incluir esta información semántica en el modelo, el rendimiento no mejoró, lo que indica que el título solo no ayuda mucho a predecir la popularidad. En conclusión, la popularidad de una canción depende de muchos factores externos, como el marketing y la fama del artista, que no están en los datos. Aun así, el modelo sirve para identificar canciones con bajo potencial comercial basándose en sus atributos técnicos.

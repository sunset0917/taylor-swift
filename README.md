# Taylor Swift Análisis de Canciones



### Dataset

Se elaboró un [dataset](data/Taylor_Swift_Data.xlsx) de las canciones de Taylor Swift. Para esto, se tomaron las versiones deluxe de todos los álbumes cuando estuvieron disponibles y se usaron las Taylor's Version; a excepción de cuando no existía, se usaba el álbum original. Se considera hasta el álbum **"The Life of a Showgirl: Encore"**

En el dataset, se incluyen los siguientes campos: 
- **Album**: Nombre del álbum. Tipo str
- **Track Number**: Número de track dentro del álbum. Tipo init
- **Taylor Version**: Si la canción es Taylor's Version. Tipo Booleano
- **Song Name**: Nombre de la canción. Tipo str
- **Duration (s)**: Duración de la canción en segundos. Tipo int
- **From The Vault**: Indica si la canción es del vault. Tipo Booleano
- **Lyrics**: Letra de la canción en inglés (idioma original). Tipo str. 
----

### Análisis

Se hizo análisis el cual puede ser categorizado por los siguientes tipos:
- Por número de canciones por álbum
- Por duración de canción y álbum
- Por cantidad palabras (únicas y totales)
- Por el sentimiento de las letras de canciones (NLP)
----

### Resultados
<!--! [Imagen](images/n_canciones_por_album.png) -->

<div align="center">
  <img src="images/n_canciones_por_album.png" alt="Descripción de la imagen" width="400">
</div>

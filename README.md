
# FakesStorage

This project aims to build a Spanish fake news dataset with news from the Internet. The objective of this dataset is to contribute to the development of systems capable of identifying online fake news. The dataset is still a work in progress.

Este proyecto está dirigido a la construcción de un dataset de noticias falsas (o "fake news") en internet que estén en español. 
Con este dataset buscamos contribuir a la construcción de sistemas para identificar noticias falsas en internet. El dataset sigue en construcción. 




## General description
This repository was created using **Python** and can be used and adapted to download articles 
about fake news from fact-checkers' websites.

The version of the latest dataset provided in this repository includes the following files 
(`WebScraping` folder):
- `fakenewsMaldita.json`: Fake news collected from Maldita.es
- `fakenewsNewtral.json`: Fake news collected from Newtral.es
- `fakenewsFactCheck.json`: Fake news collected from FactCheck.org

Each JSON file contains the following data for each article:
| Parameter     | Data type    | Description                |
| :------------ | :----------- | :------------------------- |
| `id`          | `int`        | Unique identifier for each news article in the dataset  |
| `titulo`      | `string`     | Title of the news article |
| `link`        | `string`     | Article's link from the fact-checker |
| `words_count` | `dictionary` | The number of occurrences for each word in the body text |

## Descripción general
Este repositorio escrito en **Python** se puede utilizar y adaptar para descargar artículos 
de noticias falsas publicadas por "Fact Checkers" en sus páginas web.

La versión de este último dataset incluye los siguientes archivos (carpeta `WebScraping`):
- `fakenewsMaldita.json` : ejemplos de fake news recogidas de Maldita.es
- `fakenewsNewtral.json` : ejemplos de fake news recogidas de Newtral.es
- `fakenewsFactCheck.json`: ejemplos de fake news recogidas de FactCheck.org

Cada uno de los ficheros JSON anteriores tienen los siguientes datos para cada noticia:
| Parámetro     | Tipo de dato | Descripción                |
| :------------ | :----------- | :------------------------- |
| `id`          | `int`        | Identificador de cada noticia en el dataset  |
| `titulo`      | `string`     | Título de la noticia |
| `link`        | `string`     | Link a la noticia por el fact-checker|
| `words_count` | `dictionary` | El número de apariciones de cada palabra en el cuerpo de la noticia |

## Example / Ejemplo

```javascript
 "0": {
        "titulo": "Cuidado con la inmobiliaria Rentex: la nueva inmobiliaria fantasma que trata de hacerse con tu dinero",
        "link": "https://maldita.es/malditobulo/20211209/inmobiliaria-rentex-inmobiliaria-fantasma-hacerse-con-tu-dinero/",
        "words_count": {
            "inmobiliaria": 10,
            "rentex": 7,
            "fantasma": 2,
            "rentames": 2,
            "alquiler": 3,
            "apartamentos": 1,
            "fantasmas": 2,
            "alquilar": 3,
            "un": 7,
            "piso": 9,
            "milanuncios": 3,
            "whatsapp": 3,
            "email": 2,
            "protected": 1
            ...
        }
    }
```



## Authors / Autores

- David Bugoi: [@Dbugoi](https://github.com/Dbugoi)
- Daniela Alejandra Córdova: [@DanielaCordova](https://github.com/DanielaCordova)
- Alejandro Corpas Calvo: [@alcorpas10](https://github.com/alcorpas10)
- Javier Gómez Moraleda: [@javigom](https://github.com/javigom)
- Daniel Hernández Martínez: [@dahermar](https://github.com/dahermar)
- Erik Karlgren Domercq: [@ErikKarlgren](https://github.com/ErikKarlgren)
- Adri Turiel Charro: [@atuch17](https://github.com/atuch17)



## License / Licencia

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/alcorpas10/FakeDetecter/blob/main/LICENSE)

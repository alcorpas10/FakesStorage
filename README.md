
# FakesStorage

This project aims the construction of a spanish fake news dataset with news from the internet. The objective  of this dataset is to contribute in the development of systems capable of identifying fake news online. The dataset is still work in progress.

Proyecto dirigido a la contrucción de un dataset acerca de noticias falsas (Fake News) en internet que se encuentran en español. 
Con este dataset buscamos contribuir a la construcción de sistemas para identificar noticias falsas en internet. El dataset sigue en contrucción. 




## General description
This corpus was created by scraping different domains using **python**. It can be adapted to any other fact-checking websites.

The version of the latest dataset provided in this repository includes the following files (`WebScraping` folder):
- `fakenewsMaldita.json` : Fake news collected by Maldita.es
- `fakenewsNewtral.json` : Fake news collected by Newtral.es
- `fakenewsFactCheck.json`: Fake news collected by FactCheck.org

Each json contains the following data:
| Parameter | Data type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | Unique identifier for each news include in the dataset  |
| `titulo` | `string` | Title of the news article |
| `link` | `string` | News link from the fact-checker |
| `words_count` | `dictionary` | Words counter of the body text |




## Descripción general
Este repositorio escrito en **python** se puede utilizar y adaptar para descargar artículos 
de noticias falsas publicadas por páginas web que son Fact Checkers.

La versión de este último dataset incluye los siguientes archivos (carpeta `WebScraping`):
- `fakenewsMaldita.json` : ejemplos de fake news recogidas de Maldita.es
- `fakenewsNewtral.json` : ejemplos de fake news recogidas de Newtral.es
- `fakenewsFactCheck.json`: ejemplos de fake news recogidas de FactCheck.org

Cada uno de los json anteriores tienen los siguientes datos:
| Parámetro | Tipo de dato     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | Identificador de cada noticia en el dataset  |
| `titulo` | `string` | Título de la noticia |
| `link` | `string` | Link a la noticia por el fact-checker|
| `words_count` | `dictionary` | Contador de las palabras que están en el artículo de la noticia |

## Example

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



## Authors

- DAVID BUGOI: [@Dbugoi](https://github.com/Dbugoi)
- DANIELA ALEJANDRA CÓRDOVA: [@DanielaCordova](https://github.com/DanielaCordova)
- ALEJANDRO CORPAS CALVO: [@alcorpas10](https://github.com/alcorpas10)
- JAVIER GÓMEZ MORALEDA: [@javigom](https://github.com/javigom)
- DANIEL HERNÁNDEZ MARTÍNEZ: [@dahermar](https://github.com/dahermar)
- ERIK KARLGREN DOMERCQ: [@ErikKarlgren](https://github.com/ErikKarlgren)
- ADRIÁN TURIEL CHARRO: [@atuch17](https://github.com/atuch17)



## License

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/alcorpas10/FakeDetecter/blob/main/LICENSE)

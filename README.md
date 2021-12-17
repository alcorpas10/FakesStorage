
# FakeDetecter

Project that aims the construction of a fake news dataset with news written in spanish.
With this dataset we pretend to help in the development of a system capable of identifying fake news on the internet.

Proyecto dirigido a la contrucción de un dataset acerca de noticias falsas (Fake News) en internet que se encuentran en español. 
Con este dataset buscamos contribuir a la construcción de un sistema para identificar noticias falsas en internet.




## General description
This repository written in **python** can be used to download data about fake news 
that have been published by Fact-Checkers (websites).

This version of the dataset includes the follwing files (`WebScraping` folder):
- `fakenewsMaldita.json` : Fake news collected by Maldita.es
- `fakenewsNewtral.json` : Fake news collected by Newtral.es
- `fakenewsFactCheck.json`: Fake news collected by FactCheck.org

Each json contains the following data:
| Parameter | Data type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | News identifier inside the dataset  |
| `titulo` | `string` | News title |
| `link` | `string` | News link |
| `words_count` | `dictionary` | Words counter of the body text |

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




## Descripción general
Este repositorio escrito en **python** se puede utilizar para descargar artículos 
de noticias falsas publicadas por páginas web que son Fact Checkers.

La versión de este último dataset incluye los siguientes archivos (carpeta `WebScraping`):
- `fakenewsMaldita.json` : ejemplos de fake news recogidas de Maldita
- `fakenewsNewtral.json` : ejemplos de fake news recogidas de Newtral
- `fakenewsFactCheck.json`: ejemplos de fake news recogidas de FactCheck

Cada uno de los json anteriores tienen los siguientes datos:
| Parámetro | Tipo de dato     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `int` | Identificador de cada noticia en el dataset  |
| `titulo` | `string` | Título de la noticia |
| `link` | `string` | Link a la noticia |
| `words_count` | `dictionary` | Contador de las palabras que están en el artículo de la noticia |

## Ejemplo

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

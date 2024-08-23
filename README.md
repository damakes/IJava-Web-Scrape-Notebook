# IJava Web Scrape Notebook 

Web scraping data with the [Jsoup library](https://jsoup.org/) from a [web](https://fi.wikipedia.org/wiki/Luettelo_Suomen_kuntien_koordinaateista) page and saving it to a [CSV](csv/Suomen_kuntien_koordinaatit.csv) file. I Utilized the [IJava kernel](https://github.com/SpencerPark/IJava?tab=readme-ov-file#installing), which supports Java code in a Jupyter [notebook](javaScrape.ipynb) environment. The extracted data includes a list of coordinates of Finnish municipalities. 
```console
    Location, Latitude, Longitude
    Akaa, 61.167145977°N, 23.865888764°E
    Alajärvi, 61.167145977°N, 23.865888764°E
    Alavieska, 61.167145977°N, 23.865888764°E
    Alavus, 61.167145977°N, 23.865888764°E
    Asikkala, 61.167145977°N, 23.865888764°E
    Askola, 61.167145977°N, 23.865888764°E
    Aura, 61.167145977°N, 23.865888764°E
    Brändö, 61.167145977°N, 23.865888764°E
    Eckerö, 61.167145977°N, 23.865888764°E
```
## Dependencies
- libraries\ jsoup-1.18.1.jar - [Installation guide](https://jsoup.org/download)
- libraries\ ijava-1.3.0.jar - [Installation guide](https://github.com/SpencerPark/IJava?tab=readme-ov-file#installing)

### [References](docs/References.md)

![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: API and Web Data Scraping

## Feminicidio en prensa 

El objetivo de este proyecto es rastrear las noticias asociadas con feminicidio en México a partir de diferentes fuentes de prensa. Con la data se pretende determinar la tendencia política de cada fuente a partir de un análisis de strings.

---

## Metodología

* Los datos se obtuvieron a partir de web scraping con Python en ocho fuentes de prensa distintas. 
* Las fuentes consultadas fueron las siguientes : El Universal, La Prensa, La Jornada, Expansión, Heraldo de México, Crónica, Razón y el Sol de México.
* Cada vez que el código se corre las noticias se actualizan.
* Los resultados arrojados para cada caso se concentran en un DataFrame.
* Para el análisis se desarrolló una función para identificar tendencias en la forma de exponer los encabezados de las noticias para cada fuente.
* Se encontró que el feminicidio se asocia más con palabras clave como 'vandalismo', 'manifestaciones', 'protestas' y 'daños'. Y poco con palabras como 'violencia', 'víctima' y 'justicia'.


## Resources

* [Requests Library Documentation: Quickstart](http://docs.python-requests.org/en/master/user/quickstart/)
* [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Stack Overflow Python Requests Questions](https://stackoverflow.com/questions/tagged/python-requests)
* [StackOverflow BeautifulSoup Questions](https://stackoverflow.com/questions/tagged/beautifulsoup)

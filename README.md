# hkvfewspy
python wrapper for data portal

# installation
`pip install hkvportal`

# usage
```
import hkvportal
dp = hkvportal.Service(url, uid)
```

In de dataportal kan een database worden aangemaakt (`create_database`). In een bestaande database mogen entries worden:
- aangemaakt (`new_entry`)
- bijgewerkt (`update_entry`)
- opgehaald (`get_entry`) of 
- verwijderd (`delete_entry`)

Bekijk [deze](https://tsws.hkvservices.nl/mangrove.ws/data.ashx?function=dataportal.db.getdata&parameters=%7Bdatabase:%27hoek%27,key:%27addmedia_html%27%7D&contentType=text/html) notebook om bestaande bestanden van je lokale PC in de dataportal te plaatsen 

Daarnaast zijn in the notebook folder zijn een aantal jupyter notebooks te vinden met voorbeelden van de beschikbare functies en welke typen data er in de dataportal geupload kunnen worden en hoe deze weer uit te lezen wanneer je vanuit Python werkt.
- [overview functions hkvportal](https://nbviewer.jupyter.org/github/HKV-products-services/hkvportal/blob/master/notebooks/overview%20functions.ipynb)
- [overview writing data in portal](https://nbviewer.jupyter.org/github/HKV-products-services/hkvportal/blob/master/notebooks/overview%20set%20content-types.ipynb)
- [overview reading data from portal](https://nbviewer.jupyter.org/github/HKV-products-services/hkvportal/blob/master/notebooks/overview%20get%20content-types.ipynb)

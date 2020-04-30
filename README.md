# Scraping cartosantesen

Extraction données de la situation du Covid-19 au Sénégal sur https://cartosantesen.maps.arcgis.com

## Plate-forme

[ArcGIS REST Services Directory](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services)

### Services

* [Carte_sanitaire_Kaolack](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Carte_sanitaire_Kaolack/FeatureServer) (FeatureServer)
* [Carte_sanitaire_RM_Kaolack](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Carte_sanitaire_RM_Kaolack/FeatureServer) (FeatureServer)
* [Décès](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/D%c3%a9c%c3%a8s/FeatureServer) (FeatureServer)
* [Dispositif_GMT2017](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Dispositif_GMT2017/FeatureServer) (FeatureServer)
* [Fil_Actualité_](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Fil_Actualit%c3%a9_/FeatureServer) (FeatureServer)
* [Guéris](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Gu%c3%a9ris/FeatureServer) (FeatureServer)
* [Importés_Locaux](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Import%c3%a9s_Locaux/FeatureServer) (FeatureServer)
* [Nombre_de_cas_par_jour](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Nombre_de_cas_par_jour/FeatureServer) (FeatureServer)
* [Pharmacie](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Pharmacie/FeatureServer) (FeatureServer)
* [Photos_CS_KL](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Photos_CS_KL/FeatureServer) (FeatureServer)
* [PPS_MSAS](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/PPS_MSAS/FeatureServer) (FeatureServer)
* [Situation_du_Covid_19_au_Sénégal](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Situation_du_Covid_19_au_S%c3%a9n%c3%a9gal/FeatureServer) (FeatureServer)
* [Structure_soins](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Structure_soins/FeatureServer) (FeatureServer)
* [Total_Cas_Afrique_et_monde](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Total_Cas_Afrique_et_monde/FeatureServer) (FeatureServer)
* [Total_confirmés](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/ArcGIS/rest/services/Total_confirm%c3%a9s/FeatureServer) (FeatureServer)
* [Shape__Area](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Situation_Covid19_Mise_a_jour/FeatureServer/1/query?f=json&returnGeometry=true&spatialRel=esriSpatialRelIntersects&geometry=%7B%22xmin%22%3A-1878516.4071409777%2C%22ymin%22%3A1252344.27142898%2C%22xmax%22%3A-1252344.27142898%2C%22ymax%22%3A1878516.4071409777%2C%22spatialReference%22%3A%7B%22wkid%22%3A102100%7D%7D&geometryType=esriGeometryEnvelope&inSR=102100&outFields=*&outSR=102100&resultType=tile)


## Requetes


* Carte_sanitaire_Kaolack
* Carte_sanitaire_RM_Kaolack
* [Décès](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/D%C3%A9c%C3%A8s/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&resultOffset=0&resultRecordCount=50&cacheHint=true
)
* Dispositif_GMT2017
* [Fil_Actualité_](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Fil_Actualit%C3%A9_/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&orderByFields=Date%20desc&resultOffset=0&resultRecordCount=25&cacheHint=true)
* [Guéris](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Gu%C3%A9ris/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&resultOffset=0&resultRecordCount=50&cacheHint=true
)
* [Importés_Locaux](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Import%C3%A9s_Locaux/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&outStatistics=%5B%7B%22statisticType%22%3A%22avg%22%2C%22onStatisticField%22%3A%22Cas_contacts_et_communautaires%22%2C%22outStatisticFieldName%22%3A%22Cas_contacts_et_communautaires%22%7D%2C%7B%22statisticType%22%3A%22avg%22%2C%22onStatisticField%22%3A%22Cas_importes%22%2C%22outStatisticFieldName%22%3A%22Cas_importes%22%7D%5D&cacheHint=true
)
* [Nombre_de_cas_par_jour](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Nombre_de_cas_par_jour/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&resultOffset=0&resultRecordCount=2000&cacheHint=true
)
* Pharmacie
* Photos_CS_KL
* PPS_MSAS
* Situation_du_Covid_19_au_Sénégal
* [Structure_soins](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Situation_Covid19_Mise_a_jour/FeatureServer/0/query?f=json&returnGeometry=true&spatialRel=esriSpatialRelIntersects&geometry=%7B%22xmin%22%3A-1878516.4071409777%2C%22ymin%22%3A1252344.27142898%2C%22xmax%22%3A-1252344.27142898%2C%22ymax%22%3A1878516.4071409777%2C%22spatialReference%22%3A%7B%22wkid%22%3A102100%7D%7D&geometryType=esriGeometryEnvelope&inSR=102100&outFields=*&outSR=102100&resultType=tile)
* [Total_Cas_Afrique_et_monde](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Total_Cas_Afrique_et_monde/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&resultOffset=0&resultRecordCount=50&cacheHint=true
)
* [Total_confirmés](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Total_confirm%C3%A9s/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&resultOffset=0&resultRecordCount=50&cacheHint=true
)
* [Total_confirmés_détails](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Situation_Covid19_Mise_a_jour/FeatureServer/0/query?f=json&where=1%3D1&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&orderByFields=Cas_conf%20desc&resultOffset=0&resultRecordCount=25&cacheHint=true)
* [Total_confirmés_détails_geo](https://services7.arcgis.com/Z6qiqUaS6ImjYL5S/arcgis/rest/services/Situation_Covid19_Mise_a_jour/FeatureServer/0/query?f=json&returnGeometry=true&spatialRel=esriSpatialRelIntersects&geometry=%7B%22xmin%22%3A-2504688.5428529754%2C%22ymin%22%3A1252344.27142898%2C%22xmax%22%3A-1878516.4071409777%2C%22ymax%22%3A1878516.4071409777%2C%22spatialReference%22%3A%7B%22wkid%22%3A102100%7D%7D&geometryType=esriGeometryEnvelope&inSR=102100&outFields=*&outSR=102100&resultType=tile)


## Comment signalez une erreur

Nous vous invitons à signaler les erreurs [**ICI**](https://github.com/OpenCOVID19-Senegal/scraping-cartosantesen/issues)

## Comment suggérez une nouvelle fonctionnalité

Nous vous invitons à poster vos suggestions [**ICI**](https://github.com/OpenCOVID19-Senegal/scraping-cartosantesen/pulls)

## Auteurs

* **Mamadou Diagne**


## Licence

2020 © Les contributeurs du dépôt.

Le contenu du dépôt est publié sous licence [Unlicense](https://spdx.org/licenses/Unlicense.html).

## Source

* **République du Sénégal** - *Ministère de la Santé et l’Action sociale*

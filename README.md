# Anàlisi dels factors sociodemogràfics que afecten al comportament de vot als EEUU

## Autors

Aquest repositori i els arxius que conté han estat elaborats per Ferran Castel i David Trepat, alumnes de la UOC

## Descripció
Aquest repositori conté tots els arxius necessàris per poder visualitzar l'anàlisi de vot en les eleccions americanes de l'any 2020 (Trump vs Biden) i poder veure quins factors demogràfics influeixen en el comportament de vot de la societat americana.

L'estructura del directori és:

  * /data: trobem tots els datasets que composen l'anàlisi. Es composa de:

    - /source: conté els datasets originals extrets de Kaggle. Concretament, conté:
      * county_demographics.csv: és el dataset principal del treball. Conté dades demogràfiques i socioeconòmiques a nivell de comtat americà (Font: https://www.kaggle.com/datasets/mexwell/us-country-demographics).
      * president_county_candidate.csv: conté les dades electorals de les eleccions presidencials americanes de l'any 2020 per comptat (Font: https://www.kaggle.com/datasets/unanimad/us-election-2020).
      * uscities.csv: conté les dades de les ciutats americanes, amb dades per comtat i estat (Font: Font: https://www.kaggle.com/datasets/louise2001/us-cities).
    - final_dataset.csv: és el dataset final integrat i objecte d'anàlisis.
                   
  * /code: trobem el fitxer .rmd amb el codi a partir del qual s'ha realitzat l'anàlisis.

## Llicència
El contingut d'aquest projecte està sota llicència [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/), i el codi font usat està sota llicència [MIT license](http://opensource.org/licenses/mit-license.php).

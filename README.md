# Contents

`code/`: Analysis code.  
         The main analysis file is `vaccination-indicators.Rmd`.   
         Some results are exported in `out*.RData` files.   

`data/`: Data used for the analysis.  
         The data are treated by the `code/0_INSEE_predictors.R` script, and saved as `code/data_indicators.RData`, which is the file used for analysis.

`ms/`: Manuscript files.          

# Data Sources

-  Vaccination data from Assurance Maladie:  
   -  EPCI: <https://datavaccin-covid.ameli.fr/explore/dataset/donnees-devaccination-par-epci/>
   -  Paris, Marseille, Lyon: <https://datavaccin-covid.ameli.fr/explore/dataset/donnees-de-vaccination-parcommune/information/>

-  Geographic information:
   -  EPCI: <https://datavaccin-covid.ameli.fr/explore/dataset/georef-france-epci/>
   - Paris, Marseille, Lyon: <https://datavaccin-covid.ameli.fr/explore/dataset/georef-france-commune-arrondissement-municipal/>

-  Socio-economic indicators from INSEE: <https://www.insee.fr/fr/statistiques/5359146#consulter>

-  2017 Presidential election:
   -  <https://www.data.gouv.fr/fr/datasets/election-presidentielle-des-23-avril-et-7-mai-2017-resultats-definitifs-du-1er-tour-par-communes/#resource-d282e53a-d273-425d-95bb-8a0d7632c79a-header>   
https://www.data.gouv.fr/fr/datasets/election-presidentielle-des-23-avril-et-7-mai-2017-resultats-du-2eme-tour-2/
   -  Paris: <https://opendata.paris.fr/explore/dataset/elections-presidentielles-2017-1ertour/export/?disjunctive.id_bvote&disjunctive.num_circ&disjunctive.num_quartier&disjunctive.num_arrond&sort=-num_arrond>  
   -  Marseille: <https://trouver.datasud.fr/dataset/82a6d91c-c81d-423c-9a4a-3f76d121c8ce/resource/03e2ef07-c2d0-41dd-b503-26910ecb15c3/download/marseille_presidentielles2017_tour1.csv>  
   -  Lyon: <https://www.interieur.gouv.fr/Elections/Les-resultats/Presidentielles/elecresult__presidentielle-2017/(path)/presidentielle-2017/084/069/069L.html>

# OSLO_codelijst_generator

Dit Python script zet deze excel lijst:

![image](https://github.com/samuvack/OSLO_codelijst_generator/assets/15192194/1fb9e1e3-066b-417d-86f3-58b7ad99af56)


om naar:

<code>

@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.vlaanderen.be/id/conceptscheme/VkmVoertuigType>  a skos:ConceptScheme ;
<https://www.w3.org/ns/adms#status> <https://wegenenverkeer.data.vlaanderen.be/id/concept/VkmStatus/ingebruik> ;
skos:prefLabel "VoertuigType"@nl ;
skos:definition "Codelijst van voertuigtypes"@nl .

<https://data.vlaanderen.be/id/concept/VkmVoertuigType/voetganger>  a skos:Concept ;
<https://www.w3.org/ns/adms#status> <https://wegenenverkeer.data.vlaanderen.be/id/concept/VkmStatus/ingebruik> ;
skos:definition "een persoon die zich te voet verplaatst"@nl ;
skos:inscheme <https://data.vlaanderen.be/id/conceptscheme/VkmVoertuigType> ;
skos:notation "ped" ;
skos:prefLabel "voetganger"@nl ;
skos:topConceptOf <https://data.vlaanderen.be/id/conceptscheme/VkmVoertuigType> .

<https://data.vlaanderen.be/id/concept/VkmVoertuigType/fietser>  a skos:Concept ;
<https://www.w3.org/ns/adms#status> <https://wegenenverkeer.data.vlaanderen.be/id/concept/VkmStatus/ingebruik> ;
skos:definition "een tweewielig voertuig"@nl ;
skos:inscheme <https://data.vlaanderen.be/id/conceptscheme/VkmVoertuigType> ;
skos:notation "bike" ;
skos:prefLabel "fietser"@nl ;
skos:topConceptOf <https://data.vlaanderen.be/id/conceptscheme/VkmVoertuigType> .
</code>

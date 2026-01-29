# Miljødirektoratets instruks - NiN-QGIS-setup for testing

QGIS-prosjekt for testkartlegging satt opp med utgangspunkt i [NHM's NiN-QGIS-plugin](https://github.com/geco-nhm/nin-qgis-plugin)

Oppsettet er laget for første uttesting av miljødirektoratets nye instruks for terrestrisk kartlegging av naturtyper. 
Merk at alt fortsatt er tentativt og testen gjøres for å stille overordnede spørsmål om formatet på kartleggingen som har blitt foreslått så langt. Endringer kan komme. 
Det forenklede oppsettet i disse filene representerer heller ikke det fulle kartleggingsformatet som er foreslått. 

Målgruppen er testkartleggere i Miljødirektoratets referansegruppe i prosjektet Videreutvikling av Miljødirektoratets instruks. Filene ligger likevel åpent tilgjengelig og kan brukes av alle som ønsker det.

## Veiledning

1. installer QGIS
1. klon (last ned) dette repository
1. åpne QGIS
1. åpne prosjektfila `MI_skrivebordstest_1.qgz`
1. bruk kartlaget `nin_polygons_HELDEKKENDE` og `nin_polygons_UTVALG` til å kartlegge
1. redigering og bruk av pluginen er beskrevet i f.eks. [QGIS-dokumentasjon](https://docs.qgis.org/3.40/en/docs/user_manual/working_with_vector/editing_geometry_attributes.html#editing)
1. ferdige kartlag eksporteres ved høyreklikk>Export>Save Features As... i GeoPackage-format. Husk å lagre begge kartlagene.

# Portfolio_Wildfires

o  Ce travail personel a pour objectif est de dégager les corrélations entre les caractéristiques envionnementales de forêts et la taille des incendies qui y sont déclarés.

o  Points techniques abordés:
- les données utilisées: incendies (taille, date, lieu, etc), météo, composition des forêts et sols;
- nettoyage et préparation des dataframes : jointure, utilisation de Geopandas (conversion et projection), datetime;
- description statistique: considération spatiales et temporelles à l'échelle nationale et départementale;
- étude de corrélations: test du Chi², ANOVA, régression linéaire;
- réductions par ACP: éboulis des valeurs propres, cercles de corrélations et plans factoriels, contributions;
- classifications des incendies et tests de différenciation: CAH et K-Means;
- analyse du profil des feux avec étude des clusters: projection sur plans factoriels,
- incidence des sols sur les feux.

o  Les données sont accessibles aux sites suivants:

- "IGN – Inventaire forestier national français, Données brutes, Campagnes annuelles 2005 et suivantes:  https://inventaire-forestier.ign.fr/dataIFN/, site consulté le 01/08/2022"

- Archives météorologiques publiques de Météo France:  https://donneespubliques.meteofrance.fr/?fond=produit&id_produit=90&id_rubrique=32

- Données géographiques des communes françaises:  https://geoservices.ign.fr/adminexpress#telechargement

- Base de Données sur les Incendies de forêt:  bdiff.agriculture.gouv.fr/incendies

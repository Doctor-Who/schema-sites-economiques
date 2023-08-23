## schema-site-economique

Standard CNIG Site Economique

Sp�cification du fichier d'�change conforme au standard CNIG Site Economique pour la classe POLE-ECO : P�le �conomique 

- Sch�ma cr�� le : 08/22/23
- Site web : https://github.com/cnigfr/schema-zones-activites-economiques
- Version : v1.0.0
- Valeurs manquantes : `""`, `"NA"`, `"NaN"`, `"N/A"`
- Cl� primaire�: `pole_id`

### Mod�le de donn�es

|Nom|Type|Description|Exemple|Propri�t�s|
|-|-|-|-|-|
|pole_id (identifiant)|cha�ne de caract�res|identifiant du p�le �conomique d�fini dans le standard CNIG Site Economique|44003_POLE-ECO_00162|Valeur obligatoire|
|pole_nom (nom)|cha�ne de caract�res|nom usuel du p�le �conomique|Apt activit�s|Valeur obligatoire|
|pole_vocadomi (vocation dominante)|cha�ne de caract�res|vocation dominante du p�le �conomique, issue de la vocation dominante des sites �conomiques le constituant.|mixte � dominante industrielle|Valeur obligatoire, Valeurs autoris�es�: mixte � dominante commerciale, mixte � dominante logistique, mixte � dominante industrielle, mixte � dominante tertiaire|
|pole_identif_date (date d'identification)|date (format `%Y-%m-%d`)|date d'identification du p�le �conomique|2016-03-26|Valeur obligatoire|
|pole_actu_date (date de derni�re actualisation)|date (format `%Y-%m-%d`)|date de derni�re actualisation des informations sur le p�le �conomique.|2022-08-22|Valeur optionnelle|
|pole_nb_etab (nombre d'�tablissements)|nombre entier|nombre d'�tablissements du p�le �conomique|38|Valeur optionnelle|
|pole_nb_emploi (nombre d'emploi)|nombre entier|nombre total d'emplois du p�le �conomique|1152|Valeur optionnelle|
|pole_surface (surface )|nombre entier|somme des surfaces des sites �conomiques constituant le p�le|21|Valeur optionnelle|
|pole_geompoint (localisation)|cha�ne de caract�res|coordonn�es g�ographiques du centro�de du p�le �conomique au format WKT|POINT(49.2527 3.9815)|Valeur obligatoire|
|pole_rayonnement (rayonnement )|cha�ne de caract�res|rayonnement du p�le �conomique|r�gional|Valeur optionnelle, Valeurs autoris�es�: international, national, r�gional, local|

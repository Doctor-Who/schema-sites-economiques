## schema-site-economique

Standard CNIG Site Economique

Sp�cification du fichier d'�change conforme au standard CNIG Site Economique pour la classe POLE-ECO : P�le �conomique 

- Sch�ma cr�� le : 08/22/23
- Site web : https://github.com/cnigfr/schema-zones-activites-economiques
- Version : v1.0.0
- Valeurs manquantes : `""`, `"NA"`, `"NaN"`, `"N/A"`
- Cl� primaire�: `pole_id`

### Mod�le de donn�es


##### Liste des propri�t�s

| Propri�t� | Type | Obligatoire |
| -- | -- | -- |
| [pole_id](#identifiant---propri�t�-pole_id) | cha�ne de caract�res  | Oui |
| [pole_nom](#nom---propri�t�-pole_nom) | cha�ne de caract�res  | Oui |
| [pole_vocadomi](#vocation-dominante---propri�t�-pole_vocadomi) | cha�ne de caract�res  | Oui |
| [pole_identif_date](#date-d'identification---propri�t�-pole_identif_date) | date (format `%Y-%m-%d`) | Oui |
| [pole_actu_date](#date-de-derni�re-actualisation---propri�t�-pole_actu_date) | date (format `%Y-%m-%d`) | Non |
| [pole_nb_etab](#nombre-d'�tablissements---propri�t�-pole_nb_etab) | nombre entier  | Non |
| [pole_nb_emploi](#nombre-d'emploi---propri�t�-pole_nb_emploi) | nombre entier  | Non |
| [pole_surface](#surface----propri�t�-pole_surface) | nombre entier  | Non |
| [pole_geompoint](#localisation---propri�t�-pole_geompoint) | cha�ne de caract�res  | Oui |
| [pole_rayonnement](#rayonnement----propri�t�-pole_rayonnement) | cha�ne de caract�res  | Non |

#### identifiant - Propri�t� `pole_id`

> *Description : identifiant du p�le �conomique d�fini dans le standard CNIG Site Economique<br/>Ex : 44003_POLE-ECO_00162*
- Valeur obligatoire
- Type : cha�ne de caract�res

#### nom - Propri�t� `pole_nom`

> *Description : nom usuel du p�le �conomique<br/>Ex : Apt activit�s*
- Valeur obligatoire
- Type : cha�ne de caract�res

#### vocation dominante - Propri�t� `pole_vocadomi`

> *Description : vocation dominante du p�le �conomique, issue de la vocation dominante des sites �conomiques le constituant.<br/>Ex : mixte � dominante industrielle*
- Valeur obligatoire
- Type : cha�ne de caract�res
- Valeurs autoris�es : 
    - mixte � dominante commerciale
    - mixte � dominante logistique
    - mixte � dominante industrielle
    - mixte � dominante tertiaire

#### date d'identification - Propri�t� `pole_identif_date`

> *Description : date d'identification du p�le �conomique<br/>Ex : 2016-03-26*
- Valeur obligatoire
- Type : date (format `%Y-%m-%d`)

#### date de derni�re actualisation - Propri�t� `pole_actu_date`

> *Description : date de derni�re actualisation des informations sur le p�le �conomique.<br/>Ex : 2022-08-22*
- Valeur optionnelle
- Type : date (format `%Y-%m-%d`)

#### nombre d'�tablissements - Propri�t� `pole_nb_etab`

> *Description : nombre d'�tablissements du p�le �conomique<br/>Ex : 38*
- Valeur optionnelle
- Type : nombre entier

#### nombre d'emploi - Propri�t� `pole_nb_emploi`

> *Description : nombre total d'emplois du p�le �conomique<br/>Ex : 1152*
- Valeur optionnelle
- Type : nombre entier

#### surface  - Propri�t� `pole_surface`

> *Description : somme des surfaces des sites �conomiques constituant le p�le<br/>Ex : 21*
- Valeur optionnelle
- Type : nombre entier

#### localisation - Propri�t� `pole_geompoint`

> *Description : coordonn�es g�ographiques du centro�de du p�le �conomique au format WKT<br/>Ex : POINT(49.2527 3.9815)*
- Valeur obligatoire
- Type : cha�ne de caract�res

#### rayonnement  - Propri�t� `pole_rayonnement`

> *Description : rayonnement du p�le �conomique<br/>Ex : r�gional*
- Valeur optionnelle
- Type : cha�ne de caract�res
- Valeurs autoris�es : 
    - international
    - national
    - r�gional
    - local

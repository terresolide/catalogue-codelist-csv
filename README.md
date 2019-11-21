# catalogue-codelist-csv

Ce répertoire est utilisé pour enregistrer les spécifications des métadonnées avec les listes de code et thésaurus pour le catalogue de données ForM@Ter

## Specifications
[Métadonnées - document de travail V0.5](https://cdn.jsdelivr.net/gh/terresolide/catalogue-codelist-csv@0.5/metadonnees_formater.pdf)

## Exemples
[Métadonnées - Magnetic field serie on Khourou Guiana - ISO 19115:2007/19139 valide INSPIRE](exemples/md_series_magnetic_field.xml)

## Thesaurus
### Variables

### Plateformes

### Instruments

## Code List

### ISOTC211 
 * [Les codeLists ISOTC211 (anglais)](doc/codeList/ISOTC211_19115_2003)
 * [Une partie des codeLists ISOTC211 en bilingue](doc/codeList/ISOTC211_19115_2003_ML) Traduction en cours
 
### Thème Geologie
  * [CodeList du theme geologie bilingue](doc/codeList/geology)
### Autre Code listes
|  Nom	 | Description    | Utilisation (ISO19139)| Etat
| ------ | ------ | ------- | --- |
| [compressionCode](doc/codeList/compressionCode.csv)   | **Les méthodes de compression des données** (tar, zip...) et les instructions de décompressions | ` MD_Distribution` | 50%
| [ fmtDataCenterCode](doc/codeList/fmtDataCenterCode.csv)| **Les centres de données et services du pole Terre Solide**, leurs SNO, logo...                            |  ` MD_Keywords`  ? | 90%
| [formatCode](doc/codeList/formatCode.csv)|  **Les formats de données** | `MD_Distribution` | 01%
| [INSPIRERestrictionCode](doc/codeList/INSPIRERestrictionCode.csv)|   **Les restrictions d'accès de la directive INSPIRE**| `MD_Constraints` | Fait
| [languageCode](doc/codeList/languageCode.csv)|   **Les langues (européennes) pour les métadonnées ou données** | `MD_Metadata`, `MD_DataIdentification` | Fait
| [licenceCode](doc/codeList/licenceCode.csv)|   **Les licences sur les données**  version, url , icone... | `MD_Constraints` | 50%
| [processingLevelCode](doc/codeList/processingLevelCode.csv)|   **Niveau de traitement des données**  |  | 50%
| [spatialReferenceSystemCode](doc/codeList/spatialReferenceSystemCode.csv)|   **Les référentiels spatiaux**  |  `MD_ReferenceSystem` | 50%
| [temporalReferenceSystemCode](doc/codeList/temporalReferenceSystemCode.csv)|   **Les référentiels temporaux**  |  `MD_ReferenceSystem` | 0%
| [verticalReferenceSystemCode](doc/codeList/verticalReferenceSystemCode.csv)|   **Les référentiels verticaux**  |  `MD_ReferenceSystem` | 0%



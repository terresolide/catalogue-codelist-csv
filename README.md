# catalogue-codelist-csv

Ce répertoire est utilisé pour enregistrer les listes de code et thésaurus pour le catalogue de données ForM@Ter (liste bilingue anglais / français)

## Code List

### ISOTC211 
 * [Les codeLists ISOTC211 (anglais)](codeList/ISOTC211_19115_2003)
 * [Une partie des codeLists ISOTC211 en bilingue](codeList/ISOTC211_19115_2003_ML) Traduction en cours
 
### Thème Geologie
  * [CodeList du theme geologie bilingue](blob/master/codeList/geology)
### Autre Code listes
|  Nom	 | Description    | Utilisation (ISO19139)| Etat
| ------ | ------ | ------- | --- |
| [compressionCode](codeList/compressionCode.csvv)   | **Les méthodes de compression des données** (tar, zip...) et les instructions de décompressions | ` MD_Distribution` | 50%
| [ fmtDataCenterCode](blob/master/codeList/fmtDataCenterCode.csv)| **Les centres de données et services du pole Terre Solide**, leurs SNO, logo...                            |  ` MD_Keywords`  ? | 90%
| [formatCode](blob/master/codeList/formatCode.csv)|  **Les formats de données** | `MD_Distribution` | 01%
| [INSPIRERestrictionCode](blob/master/codeList/INSPIRERestrictionCode.csv)|   **Les restrictions d'accès de la directive INSPIRE**| `MD_Constraints` | Fait
| [languageCode](blob/master/codeList/languageCode.csv)|   **Les langues (européennes) pour les métadonnées ou données** | `MD_Metadata`, `MD_DataIdentification` | Fait
| [licenceCode](blob/master/codeList/licenceCode.csv)|   **Les licences sur les données**  version, url , icone... | `MD_Constraints` | 50%
| [processingLevelCode](blob/master/codeList/processingLevelCode.csv)|   **Niveau de traitement des données**  |  | 50%
| [spatialReferenceSystemCode](blob/master/codeList/spatialReferenceSystemCode.csv)|   **Les référentiels spatiaux**  |  `MD_ReferenceSystem` | 50%
| [temporalReferenceSystemCode](blob/master/codeList/temporalReferenceSystemCode.csv)|   **Les référentiels temporaux**  |  `MD_ReferenceSystem` | 0%
| [verticalReferenceSystemCode](blob/master/codeList/verticalReferenceSystemCode.csv)|   **Les référentiels verticaux**  |  `MD_ReferenceSystem` | 0%



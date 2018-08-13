# :bust_in_silhouette: ORGREG COVERAGE :bust_in_silhouette:

This note documents how the Lenticular Lens was used for linking entities from []OrgReg] to five other open datasets [GRID, ORGREF, ETER, H202 AND LeidenRanking]. We first linked entities based on their respective mentioned using a string approximation algorithm with a threshold of 0.8. We then refines all the dicovered links based on the organisation's country.


## 1. GRID 2018-06-25

Adding data from file: C:\Productivity\Deliverables\Coverage\grid20180625\grid.ttl
**[1,415,440 triples]** added in 00:00:42.641


## 2. ORGREF 2018-03-01

(AlignmentUI) C:\Users\Al\PycharmProjects\AlignmentUI\src>echo "Loading data"
 "Loading data"

(AlignmentUI) orgref_1_2018-08-02.trig"
 Adding data from file: orgref_1_(Meta)_2018-08-02.trig
Adding data from file: orgref_1_2018-08-02.trig
**[300,425 triples]** added in 00:00:06.962


## 3. ORGREG 2017-08-08

### University

Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\University\ORGREG_20170718__Entities_1_(Meta)_2017-08-08.trig
Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\University\ORGREG_20170718__Entities_1_2017-08-08.trig
**[20,622 triples]** added in 00:00:01.167

### Location

Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\Location\ORGREG_20170718__LOCATION_1_(Meta)_2017-08-08.trig
Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\Location\ORGREG_20170718__LOCATION_1_2017-08-08.trig
**[46,821 triples]** added in 00:00:01.712

### Demographic

Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\Demographic\ORGREG_20170718__Demographics_1_(Meta)_2017-08-08.trig
Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\Demographic\ORGREG_20170718__Demographics_1_2017-08-08.trig
**[4,105 triples]** added in 00:00:00.551

### Characteristics

Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\Characteristics\ORGREG_20170718__Characteristics_1_(Meta)_2017-08-08.trig
Adding data from file: D:\Linking2GRID\Data\OrgReg 20170718\converted\orgreg_20170718.2017-08-08\Characteristics\ORGREG_20170718__Characteristics_1_2017-08-08.trig
**[51,921 triples]** added in 00:00:01.561


## 4. LeidenRanking

Adding data from file: C:\Productivity\Deliverables\Coverage\data\Leiden Ranking 2015 extended\converted\leidenRanking_2015.2017-08-03\University\LR_results_all_orgs_1_2017-08-03.trig
Adding data from file: C:\Productivity\Deliverables\Coverage\data\Leiden Ranking 2015 extended\converted\leidenRanking_2015.2017-08-03\University\LR_results_all_orgs_1_(Meta)_2017-08-03.trig
**[39,564 triples]** added in 00:00:01.112


## 5. ETER

Adding data from file: D:\Linking2GRID\Data\ETER 2017\converted\eter_2014.2017-08-03\University\eter_export_2014_1_(Meta)_2017-08-03.trig
Adding data from file: D:\Linking2GRID\Data\ETER 2017\converted\eter_2014.2017-08-03\University\eter_export_2014_1_2017-08-03.trig
**[1,062,956 triples]** added in 00:00:12.866


## 6. H2020

Adding data from file: D:\Linking2GRID\Data\h2020-2017\cordisref-projectFundingScheme.ttl
Adding data from file: D:\Linking2GRID\Data\h2020-2017\cordis-h2020organizations-2017-parcs.ttl
Adding data from file: D:\Linking2GRID\Data\h2020-2017\cordis_h2020organizations_2017.ttl
Adding data from file: D:\Linking2GRID\Data\h2020-2017\cordisref-H2020programmes-2017.ttl
Adding data from file: D:\Linking2GRID\Data\h2020-2017\cordis-h2020projects-2017.ttl
Adding data from file: D:\Linking2GRID\Data\h2020-2017\cordisref-H2020topics.ttl
**[676,814 triples]** added in 00:00:12.360


## 7. Amadeus

Adding data from file: D:\Linking2GRID\Data\Amadeus\converted\amadeus.2016-11-24\Organisation\pro_extract4_vu.1.2016-11-24.trig
**[938,043 triples]** added in 00:00:15.624


## 8. COUNTRIES

Adding data from file: D:\Linking2GRID\Data\Countries\location_1.ttl
[**6,717 triples**] added in 00:00:00.871


## DATASETS STATISTICS

| DATASET | ENTITY TYPE | COUNT |
| --- | --- | --- |
| GRID | ORGANIZATION | 88629 |
| ORGREF | ORGANIZATION | 31792 |
| ORGREG | ORGANIZATION | 3338 |
| LEIDENRANKING | UNIVERSITY | 2823 |
| ETER | UNIVERSITY | 2764 |
| H2020 | ORGANIZATION | 16621 |
| COUNTRIES | COUNTRY | 249 |
| AMADEUS | COMPANY | 56984 |


## DATASETS AND IDENTITY PROPERTIES

| DATASET | PROPERTY |
| --- | --- |
| ORGREG | English_name_of_entity |
| ORGREG | Name_of_entity |
| ORGREF | name |
| ORGREF | Country_of_establishment (country code) |
| ORGREF | Country (country code) |
| ETER | English_Institution_Name |
| ETER | Institution_Name |
| ETER | Country_Code |
| GRID | altLabel |
| GRID | label |
| GRID | hasAddress / countryCode |
| LEIDEN RANKING | actor |
| H2020 | name |
| H2020 | country (country code) |
| GRID | altLabel |
| AMADEUS | Companyname |


## MATCHINGS

-   ETER
    

| SRC DATASET | SRC PROPERTY | TRG DATASET | TRG PROPERTY | DISCOVERED |
| --- | --- | --- | --- | --- |
| ORGREG | English_name_of_entity | ETER | English_Institution_Name | 1810 |
| ORGREG | English_name_of_entity | ETER | Institution_Name | 383 |
| ORGREG | Name_of_entity | ETER | English_Institution_Name | 354 |
| ORGREG | Name_of_entity | ETER | Institution_Name | 1790 |

LENS BY [UNION]: ORGREG - ETER - APPROX 0.8 = [1990]

LENS BY [REFINE]: ORGREG - ETER - EXACT COUNTRY CODE = [1905]

* * *

-   GRID
    

| SRC DATASET | SRC PROPERTY | TRG DATASET | TRG PROPERTY | DISCOVERED |
| --- | --- | --- | --- | --- |
| ORGREG | English_name_of_entity | GRID | altLabel | 161 |
| ORGREG | English_name_of_entity | GRID | label | 1946 |
| ORGREG | Name_of_entity | GRID | altLabel | 351 |
| ORGREG | Name_of_entity | GRID | label | 677 |

LENS BY [UNION:] ORGREG - GRID- APPROX 0.8 = [2522]

LENS BY [REFINE]: ORGREG - GRID- EXACT COUNTRY CODE = [1975]

* * *

-   ORGREF
    

| RC DATASET | SRC PROPERTY | TRG DATASET | TRG PROPERTY | DISCOVERED |
| --- | --- | --- | --- | --- |
| ORGREG | English_name_of_entity | ORGREF | name | 1262 |
| ORGREG | Name_of_entity | ORGREF | name | 282 |

LENS BY [UNION: ORGREG - ORGREF - APPROX 0.8 = 1355

LENS BY [REFINE: ORGREG - ORGREF- EXACT COUNTRY CODE = 1012

* * *

-   LEIDEN RANKING
    

| SRC DATASET | SRC PROPERTY | TRG DATASET | TRG PROPERTY | DISCOVERED |
| --- | --- | --- | --- | --- |
| ORGREG | English_name_of_entity | LEIDEN | actor | 514 |
| ORGREG | Name_of_entity | LEIDEN | actor | 167 |

LENS BY [UNION]: ORGREG - LEIDENRANKING - APPROX 0.8 = [580]

LENS BY [REFINE]: ORGREG - LEIDENRANKING - EXACT INTERMEDIATE [COUNTRY CODE] VS [COUNTRY NAME] = [482]

* * *

-   H2020
    

| RC DATASET | SRC PROPERTY | TRG DATASET | TRG PROPERTY | DISCOVERED |
| --- | --- | --- | --- | --- |
| ORGREG | English_name_of_entity | H2020 | name | 247 |
| ORGREG | Name_of_entity | H2020 | name | 689 |

LENS BY [UNION]: ORGREG - H2020 - APPROX 0.8 = [759]

LENS BY [REFINE]: ORGREG - H2020- EXACT COUNTRY CODE = [710]

* * *

-   Amadeus
    

| RC DATASET | SRC PROPERTY | TRG DATASET | TRG PROPERTY | DISCOVERED |
| --- | --- | --- | --- | --- |
| ORGREG | English_name_of_entity | Amadeus | Companyname | 39 |
| ORGREG | Name_of_entity | Amadeus | Companyname | 160 |

LENS BY [UNION]: ORGREG - Amadeus - APPROX 0.8 = **[165]**

LENS BY [REFINE]: ORGREG - LEIDENRANKING - EXACT INTERMEDIATE [COUNTRY CODE] VS [COUNTRY NAME] = [159]

* * *

-   UNIION OF ALL REFINED:
    

THE LENS WAS CREATED as http://risis.eu/lens/union_Orgreg_20170718_Eter_2014_Grid_20180625_H2020_2017_LeidenRanking_2015_Orgref_20180301_P565060110. With initially [6084 triples] loaded, 0 duplicated triples were found and removed.

THE LENS WAS CREATED as http://risis.eu/lens/union_Orgreg_20170718_Amadeus_Eter_2014_Grid_20180625_H2020_2017_LeidenRanking_2015_Orgref_20180301_P1951854249. With initially 6243 triples loaded, 0 duplicated triples were found and removed.


## SPARQL QUERY

-   TOTAL NUMBER OF ORGREG RESOURCES MATCHED
    

```sql
### TOTAL NUMBER OF ORGREG RESOURCES MATCHED
PREFIX data: <http://risis.eu/dataset/>
PREFIX lens: <http://risis.eu/lens/>
PREFIX opre: <http://risis.eu/orgreg_20170718/ontology/predicate/>

SELECT  (COUNT(DISTINCT ?src_a) AS ?discovered) # ?src_a ?src_b
{
BIND(lens:union_Orgreg_20170718_Eter_2014_Grid_20180625_H2020_2017_LeidenRanking_2015_Orgref_20180301_P565060110 AS ?lens)
    GRAPH ?lens    { ?src_a ?sing ?src_b }
    GRAPH data:orgreg_20170718 
    { 
        ?src_a a ?type .
        ?src_a opre:Type_of_entity ?orgregType .
    }
}
```

| discovered |
| --- |
| 2628 | 

-   DISTRIBUTION PER TYPE OF THE DISCOVERED
    

```sql
### TOTAL NUMBER OF ORGREG RESOURCES MATCHED
PREFIX data: <http://risis.eu/dataset/>
PREFIX lens: <http://risis.eu/lens/>
PREFIX opre: <http://risis.eu/orgreg_20170718/ontology/predicate/>

SELECT  ?orgregType (COUNT(DISTINCT ?src_a) AS ?discovered)  # ?src_a ?src_b
{
 BIND(lens:union_Orgreg_20170718_Eter_2014_Grid_20180625_H2020_2017_LeidenRanking_2015_Orgref_20180301_P565060110 AS ?lens)
    GRAPH ?lens    { ?src_a ?sing ?src_b }
    GRAPH data:orgreg_20170718 
    { 
        ?src_a a ?type .
        ?src_a opre:Type_of_entity ?orgregType .
    }
} GROUP BY ?orgregType ORDER BY desc(?total)
```

| OrgregType | discovered |
| --- | --- |
| HEI | 1928 |
| PRO | 451 |
| research hospital | 177 |
| PNP | 36 |
| GOV | 29 |
| HEI,research hospital | 4 |
| HEI PRO | 2 |
| PRO research hospital | 1 |

```sql

### TOTAL NUMBER OF ORGREG RESOURCES MATCHED
PREFIX data: <http://risis.eu/dataset/>
PREFIX lens: <http://risis.eu/lens/>
PREFIX opre: <http://risis.eu/orgreg_20170718/ontology/predicate/>

SELECT  ?orgregType (COUNT(DISTINCT ?src_a) AS ?total)
{  BIND(lens:union_Orgreg_20170718_Eter_2014_Grid_20180625_H2020_2017_LeidenRanking_2015_Orgref_20180301_P565060110 AS ?lens)        
  GRAPH ?lens    { ?src_a ?sing ?src_b }
    GRAPH data:grid_20180625 { ?src_b a ?gridtype . }
  GRAPH data:orgreg_20170718 
    { 
        ?src_a a ?type .
        ?src_a opre:Type_of_entity ?orgregType .
    }
} GROUP BY ?orgregType ORDER BY desc(?total)
```

| orgregType | TOTAL | GRID | ORGREF | H2020 | LEIDEN | ETER | AMADEUS |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HEI | 1928 | 1273 | 834 | 462 | 349 | 1801 | 94 |
| PRO | 451 | 397 | 73 | 184 | 64 | - | 46 |
| research hospital | 177 | 160 | 44 | 28 | 41 | 2 | 16 |
| PNP | 36 | 33 | 4 | 8 | 6 | - | 2 |
| GOV | 29 | 27 | 4 | 12 | 6 | - | 1 |
| HEI,research hospital | 4 | 3 | 1 | 2 | 1 | 4 | - |
| HEI PRO | 2 | 2 | 2 | 2 | 1 | 1 | - |
| PRO research hospital | 1 | 1 | - | - | - | - | - |
| TOTAL | 2628 | 1896 | 962 | 698 | 468 | 1808 | 159 |

| gridtype | discovered |
| --- | --- |
| [foaf:Organization](http://xmlns.com/foaf/0.1/Organization) | 1804 |
| [http://www.grid.ac/ontology/Education](http://www.grid.ac/ontology/Education) | 1111 |
| [http://www.grid.ac/ontology/Facility](http://www.grid.ac/ontology/Facility) | 240 |
| [http://www.grid.ac/ontology/Healthcare](http://www.grid.ac/ontology/Healthcare) | 170 |
| [http://www.grid.ac/ontology/Nonprofit](http://www.grid.ac/ontology/Nonprofit) | 93 |
| [http://www.grid.ac/ontology/Government](http://www.grid.ac/ontology/Government) | 44 |
| [http://www.grid.ac/ontology/Other](http://www.grid.ac/ontology/Other) | 40 |
| [http://www.grid.ac/ontology/Company](http://www.grid.ac/ontology/Company) | 16 |
| [http://www.grid.ac/ontology/Archive](http://www.grid.ac/ontology/Archive) | 11 |

| orgrefTypes | discovered |
| --- | --- |
| Org | 908 |
| Sub | 4 |

| h2020Types | discovered |
| --- | --- |
| [http://risis.eu/cordisH2020/resource/organizationType_HES](http://risis.eu/cordisH2020/resource/organizationType_HES) | 446 |
| [http://risis.eu/cordisH2020/resource/organizationType_REC](http://risis.eu/cordisH2020/resource/organizationType_REC) | 197 |
| [http://risis.eu/cordisH2020/resource/organizationType_PUB](http://risis.eu/cordisH2020/resource/organizationType_PUB) | 15 |
| [http://risis.eu/cordisH2020/resource/organizationType_PRC](http://risis.eu/cordisH2020/resource/organizationType_PRC) | 13 |
| [http://risis.eu/cordisH2020/resource/organizationType_OTH](http://risis.eu/cordisH2020/resource/organizationType_OTH) | 6 |

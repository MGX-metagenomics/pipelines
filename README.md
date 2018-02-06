This is the repository of public MGX pipelines.

Field description:
 Name: Short pipeline name
 Description: Pipeline description
 Author: Pipeline maintainer
 URL: Web site with additional pipeline information
 Version: Pipeline version
 File: Conveyor-based pipeline implementation

All pipelines should use 0-based coordinates when creating sequence
observations.


## Quality control

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
| Read length   | Distribution of sequence length | Sebastian Jaenicke | - | 1.0 |GC.xml |
| GC content    | Distribution of GC content | Sebastian Jaenicke | - | 1.0 |readlength.xml |

## Taxonomic assignment

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
| Centrifuge || Sebastian Jaenicke | - | 1.0 |centrifuge.xml |
| Kaiju || Sebastian Jaenicke | - | 1.0 |kaiju.xml |
| Kraken || Sebastian Jaenicke | - | 1.0 |kraken.xml |
| MetaBin || Sebastian Jaenicke | - | 1.0 |metabin.xml |
| MetaCV || Sebastian Jaenicke | - | 1.0 |metacv.xml |
| MetaPhlAn || Sebastian Jaenicke | - | 1.0 |metaphlan.xml |
| MetaPhlAn2 || Sebastian Jaenicke | - | 1.0 |metaphlan2xml |
| MetaPhyler || Sebastian Jaenicke | - | 1.0 |metaphyler.xml |
||| Sebastian Jaenicke || 1.0 | rdp_pipeline.xml |


## Functional profiling

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
||| Sebastian Jaenicke | - | 1.0 | eggnog.xml |
||| Sebastian Jaenicke | - | 1.0 | ecnumber.xml |
||| Sebastian Jaenicke | - | 1.0 | fungene.xml |
||| Sebastian Jaenicke | - | 1.0 | dbCAN_besthit.xml |
||| Sebastian Jaenicke | - | 1.0 | clustermine360.xml |
||| Sebastian Jaenicke | - | 1.0 | pfam_besthit.xml |
||| Sebastian Jaenicke | - | 1.0 | tigrfam_besthit.xml |

## Antimicrobial resistance

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
| ARDB || Sebastian Jaenicke | - | 1.0 |ardb.xml |
| ARG-Annot || Sebastian Jaenicke | - | 1.0 |argannot.xml |
| BacMet ||Sebastian Jaenicke | - | 1.0 |bacmet.xml |
| CARD || Sebastian Jaenicke | - | 1.0 |card.xml |
| MVirDB || Sebastian Jaenicke | - | 1.0 |mvirdb.xml |

## Reference mapping

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
||| Sebastian Jaenicke | - | 1.0 |blastn_refmap.xml |
||| Sebastian Jaenicke | - | 1.0 |bowtie_refmap.xml |
||| Sebastian Jaenicke | - | 1.0 |frhit_refmap.xml |

## Amplicon analysis

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
||| Sebastian Jaenicke | - | 1.0 |mothur_custom.xml |
||| Sebastian Jaenicke | - | 1.0 |mothur_its.xml |
||| Sebastian Jaenicke | - | 1.0 |mothur_silva.xml |
||| Sebastian Jaenicke | - | 1.0 |rdp_amplicons.xml |
||| Sebastian Jaenicke | - | 1.0 |qiime_assignTaxonomy.xml |


## Misc

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
||| Sebastian Jaenicke | - ||besthit_aa.xml |
||| Sebastian Jaenicke | - ||besthit_nt.xml |
||| Sebastian Jaenicke | - ||discard_rRNAs.xml |
||| Sebastian Jaenicke | - ||ecolifilter.xml |
||| Sebastian Jaenicke | - ||lca_nr_ghostx.xml |
||| Sebastian Jaenicke | - ||lca_nr_rapsearch.xml |
||| Sebastian Jaenicke | - ||lca_nr.xml |
||| Sebastian Jaenicke | - ||lca_pipeline.xml |
||| Sebastian Jaenicke | - ||phageprotscreen.xml |
||| Sebastian Jaenicke | - ||phagescreen.xml |
||| Sebastian Jaenicke | - ||pks.xml |
||| Sebastian Jaenicke | - ||plasmidprotscreen.xml |
||| Sebastian Jaenicke | - ||referencefilter.xml |
||| Sebastian Jaenicke | - ||swissprot.xml |



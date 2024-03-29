This is the central repository of public MGX pipelines.

Field description:
 - Name: Short pipeline name
 - Description: Pipeline description
 - Author: Pipeline maintainer
 - URL: Web site with additional pipeline information
 - Version: Pipeline version
 - File: Conveyor workflow for read-based analysis
 - File2: Conveyor workflow for gene annotation

All pipelines should use 0-based coordinates when creating sequence
observations.

## Taxonomic assignment

| Name          | Description   | Author | URL | version | file | file2 |
| ------------- | ------------- | ------ | --- | ------- | ---- | ---- |
| MGX default taxonomy | MGX default taxonomic classification based on Kraken and Diamond vs. RefSeq proteins | Sebastian Jaenicke | - | 1.0 | mgx_default_taxonomy.xml |
| Centrifuge | Centrifuge: rapid and sensitive classification of metagenomic sequences | Sebastian Jaenicke | - | 1.0 | centrifuge.xml | mgxgene_centrifuge.xml |
| Kaiju | Kaiju: Fast and sensitive taxonomic classification for metagenomics | Sebastian Jaenicke | - | 1.0 | kaiju.xml | mgxgene_kaiju.xml |
| Kraken | Kraken: ultrafast metagenomic sequence classification using exact alignments | Sebastian Jaenicke | - | 1.0 | kraken.xml |
| KrakenUniq | Taxonomic sequence classification with KrakenUniq | Sebastian Jaenicke | - | 1.0 | krakenuniq.xml |
| Kraken 2 | Kraken: ultrafast metagenomic sequence classification using exact alignments | Sebastian Jaenicke | - | 1.0 | kraken2.xml | mgxgene_kraken2.xml |
| MetaPhlAn 4 | MetaPhlAn 4 marker-based taxonomic classification | Sebastian Jaenicke | - | 1.0 | metaphlan4.xml |
| 16S Pipeline | Classification of 16S rRNA fragments | Sebastian Jaenicke || 1.0 | rdp_pipeline.xml |


## Functional profiling

| Name          | Description   | Author | URL | version | file | file2 |
| ------------- | ------------- | ------ | --- | ------- | ---- | ----- |
| COG | COG-based functional classification | Sebastian Jaenicke | - | 1.0 | eggnog.xml | mgxgene_eggnog.xml |
| SwissProt EC numbers | EC number annotation based on best-Blast-hit vs. SwissProt database | Sebastian Jaenicke | - | 1.0 | ecnumber.xml | mgxgene_ecnumber.xml |
| FunGene HMM search | HMM search vs. FunGene functional genes | Sebastian Jaenicke | - | 1.0 | fungene.xml | mgxgene_fungene.xml |
| dbCAN | Automated Carbohydrate-active enzyme annotation based on dbCAN | Sebastian Jaenicke | - | 1.0 | dbCAN_besthit.xml | mgxgene_dbcan.xml |
| ClusterMine360 | PKS/NRPS analysis based on BLAST vs ClusterMine360 database | Sebastian Jaenicke | - | 1.0 | clustermine360.xml | mgxgene_clustermine360.xml |
| Pfam | Annotate best Pfam domain hit | Sebastian Jaenicke | - | 1.0 | pfam_besthit.xml | mgxgene_pfam.xml |
| TIGRFAMS | Annotate best TIGRFAMS domain hit | Sebastian Jaenicke | - | 1.0 | tigrfam_besthit.xml | mgxgene_tigrfam.xml |
| PGAP| Annotate best NCBI PGAP HMM hit | Sebastian Jaenicke | - | 1.0 | pgap.xml | mgxgene_pgap.xml | 
| MIBiG | MIBiG secondary metabolite screening | Sebastian Jaenicke | - | 1.0 | mibig.xml | mgxgene_mibig.xml |
| KOfam | KO number annotation | Sebastian Jaenicke | - | 1.0 | kofam.xml | mgxgene_kofam.xml |
| UniRef50 | UniRef50 annotation | Sebastian Jaenicke | - | 1.0 | uniref50.xml | mgxgene_uniref50.xml |
| VOGDB | Virus orthologous groups | Sebastian Jaenicke | - | 1.0 | - | mgxgene_vogdb.xml |

## Antimicrobial resistance

| Name          | Description   | Author | URL | version | file | file2 |
| ------------- | ------------- | ------ | --- | ------- | ---- | ----- |
| ARDB | Antibiotic resistance gene annotation using best Blast hit vs. ARDB database | Sebastian Jaenicke | - | 1.0 | ardb.xml | mgxgene_ardb.xml |
| ARG-Annot | Antibiotic resistance gene annotation using best Blast hit vs. ARG-ANNOT database | Sebastian Jaenicke | - | 1.0 | argannot.xml |
| BacMet | Antibacterial biocide- and metal-resistance gene annotation using best Blast hit vs. BacMet database | Sebastian Jaenicke | - | 1.0 | bacmet.xml | mgxgene_bacmet.xml |
| CARD | Antibiotic resistance gene screening using Blast vs CARD (Comprehensive antibiotic resistance database) | Sebastian Jaenicke | - | 1.0 | card.xml | mgxgene_card.xml |
| MVirDB | MvirDB-based virulence analysis | Sebastian Jaenicke | - | 1.0 | mvirdb.xml | mgxgene_mvirdb.xml |
| AMRFinder+ | NCBI AMRFinder+ | Sebastian Jaenicke | - | 1.0 | - | mgxgene_amrfinder.xml |

## Reference mapping

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
| FR-HIT | Fragment recruitment based on NCBI Magic-BLAST | Sebastian Jaenicke | - | 1.0 | blastn_refmap.xml |
| Bowtie2 | Bowtie2-based reference mapping | Sebastian Jaenicke | - | 1.0 | bowtie_refmap.xml |
| Blast-Mapping | Fragment recruitment employing FR-HIT | Sebastian Jaenicke | - | 1.0 | frhit_refmap.xml |

## Amplicon analysis

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
| 16S-Amplicons Bergey | RDP-based taxonomic assignment for 16S amplicons | Burkhard Linke | - | 1.0 | rdp_amplicons.xml |

## Misc

| Name          | Description   | Author | URL | version | file |
| ------------- | ------------- | ------ | --- | ------- | ---- |
||| Sebastian Jaenicke | - | 1.0 | besthit_aa.xml |
||| Sebastian Jaenicke | - | 1.0 | discard_rRNAs.xml |
||| Sebastian Jaenicke | - | 1.0 | ecolifilter.xml |
||| Sebastian Jaenicke | - | 1.0 | phageprotscreen.xml |
||| Sebastian Jaenicke | - | 1.0 | phagescreen.xml |
||| Sebastian Jaenicke | - | 1.0 | pks.xml |
||| Sebastian Jaenicke | - | 1.0 | plasmidprotscreen.xml |
||| Sebastian Jaenicke | - | 1.0 | referencefilter.xml |



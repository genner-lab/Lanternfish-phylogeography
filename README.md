# Lanternfish-phylogeography
Global phylogeography of lanternfish paper

Data and supplementary information for the paper "Global phylogeography of hyperdiverse lanternfishes indicates sympatric speciation in the deep sea".

Jennifer J. Freer, Geraint Tarling, Rupert A. Collins, Martin Collins, Julian C. Partridge, Martin J. Genner

FOLDER: 1_input_data

FILE: gbif_occurrences_raw_1.csv
Downloaded occurrence records of Myctophidae (family Benthosema – Hygophum) from the Global Biodiversity Information Facility (GBIF).  Records included here are the raw, unprocessed occurrence records accessed in 2016 with all GBIF associated metadata. These occurrence records underwent further quality assurance and control processes. 

FILE: gbif_occurrences_raw_2.csv
Downloaded occurrence records of Myctophidae (family Idiolychnus – Metelectrona) from the Global Biodiversity Information Facility (GBIF).  Records included here are the raw, unprocessed occurrence records accessed in 2016 with all GBIF associated metadata. These occurrence records underwent further quality assurance and control processes. 

FILE: gbif_occurrences_raw_3.csv
Downloaded occurrence records of Myctophidae (family Myctophum – Triphoturus) from the Global Biodiversity Information Facility (GBIF).  Records included here are the raw, unprocessed occurrence records accessed in 2016 with all GBIF associated metadata. These occurrence records underwent further quality assurance and control processes. 

FILE: gbif_occurrences_cleaned.csv
Cleaned and processed GBIF occurrence records of Myctophidae and the environmental conditions associated to each presence locality for use in ecological niche modelling analyses. Quality assurance and control processes included Unreliable data, which included removing records with identical latitude and longitude, and records with a latitude and longitude corresponding to a terrestrial location. Duplicate records were excluded from model runs. Environmental predictor columns include:
bathymetry = water depth (metres)
oxy_1000m = dissolved oxygen at 1000m (ml/l)
pp = net primary production of biomass expressed as carbon per unit volume in sea water (gC/m3/day)
sal_0m = salinity at 0m (PSU)
sal_1000m = salinity at 1000m (PSU)
sal_200m = salinity at 200m (PSU)
temp_1000m = temperature at 1000m (degrees celcius)
temp_oxy_0mpca1 = 1st principal component of variation between sea surface temperature and sea surface dissolved oxygen
temp_oxy_200mpca1 = 1st principal component of variation between temperature and dissolved oxygen at 200m
oceanbasin = categorical predictor indicating position within 10 main oceans and seas (Arctic Ocean, North and South Atlantic Ocean, North and South Pacific Ocean, Southern Ocean, Indian Ocean, Baltic Sea, Mediterranean Region, South China and Eastern Archipelagic Seas).

FILE: is3_photophore_images.zip
Myctophid images used as input to the Interactive Individual Identification System (IS3) software v.4.02 for photophore dissimilarity analysis.

FILE: species_depth_info.csv
Recorded maximum and minimum depth of occurrence for each Myctophid species used as input to depth overlap analysis.

FOLDER: 2_results

FILE: maxent_results_maps1.html
Output maps of ecological niche models showing the average spatial prediction of suitable habitat (MaxEnt Cloglog output) for species Benthosema fibulatum – Gonichthys tenuiculus.

FILE: maxent_results_maps2.html
Output maps of ecological niche models showing the average spatial prediction of suitable habitat (MaxEnt Cloglog output) for species Gymnoscopelus bolini – Myctophum asperum.

FILE: maxent_results_maps3.html
Output maps of ecological niche models showing the average spatial prediction of suitable habitat (MaxEnt Cloglog output) for species Myctophum aurolaternatum – Triphoturus nigrescens.

FILE: phylogeny_concat_gblock.fasta
Fasta file containing the concatenated and cleaned sequence alignments used to build phylogenetic tree of Myctophiformes.

FILE: species_pairs_overlap_comparisons.csv
Extracted values of each overlap/distance matrix for each of the 46 sister-species pairs and corresponding non-sister pairs (i.e. most recently diverged species from each pair). Information on each matrix is within folder 3_matrices

FILE: predicted_ecoregion_presence.csv
The number of cells predicted as suitable within each mesopelagic ecoregion (n=33) for each species included in ecological niche modelling (n=167). Used as input to NMDS analysis. Final row = total number of regions present per species, final column = total number of species present per ecoregion.

FOLDER: 3_matrices

FILE: matrix_depth.csv
Matrix of pairwise depth overlap between 212 lanternfish species

FILE: matrix_genetic.csv
Matrix of pairwise genetic distance between 175 lanternfish species

FILE: matrix_range.csv
Matrix of pairwise spatial range overlap between 167 lanternfish species

FILE: matrix_niche_D.csv 
Matrix of pairwise niche overlap (Schoener’s D metric) between 167 lanternfish species

FILE: matrix_niche_I.csv 
Matrix of pairwise niche overlap (I similarity metric) between 167 lanternfish species

FILE: matrix_niche_relrank.csv 
Matrix of pairwise niche overlap (relative ranks metric) between 167 lanternfish species

FILE: matrix_photophore.csv 
Matrix of pairwise photophore pattern dissimilarity between 161 lanternfish species


# Richardon-and-Gent-2024-Plant-Health-Progress

The data set is from five years of experiments (four are used) conducted to understand how various fungicides and their timing influence development of hop downy mildew. 

These files are provided to enable full reproducibility of the statistical analysis presented in the paper. We make no warranties regarding these programs.

Corresponding author: David H. Gent dave.gent@usda.gov


# Files

Data Set.csv

--Data used in the analysis. Note that period symbols indicate data was missing or not relevant for a given factor. 

SAS Code Richardson and Gent 2024 Plant Health Progress.txt

--This text file contains both the data and SAS version 9.4 code to reproduce the analyses. 


# Variable Description
The data set and SAS code associated to conduct the analysis is provided. Variable names in the data set are as follows:

Year: Year the experiment was conducted. Data from 2019 is provided but was not used because of flooding that occurred in April 2019 that resulted in uneven spring growth and confounded disease measurements.

TRT: Abbreviations for the various treatments, with fungicide treatments represented with letters to denote the specific sequence of the four applications. For instance, KKKK is Kocide-Kocide-Kocide-Kocide. KKFF is Kocide-Kocide-FungiPhite-FungiPhite.

Block: Roman numeral indicate replication (block) I to V.

AUDPC: Area under the disease progress curve calculated from disease measurements made over time.

Timing: A categorical variable indicating whether the synthetic fungicides applied in rotation with copper hydroxide were applied in the first two ('Early') or last two ('Late') applications. The nontreated control ('NT') and copper hydroxide only treatments ('Kocide') are indicated as missing for this variable.

Treatment: Product trade names are listed for ease of interpretation.

tAUDPC: squareroot transformation of AUDPC

# Other Notes
Some additional code is provided for data visualizatiosn which were not published in the paper. 

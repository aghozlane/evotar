# Evotar

The analysis of Evotar data can be performed on [shaman](shaman.pasteur.fr).

## Count and annotation files :

Connect to shaman and select section Upload your data.

### MGS analysis:

1. Select MGS table type
2. Load the count table: evotar_mgs_count_table.tsv
3. Load the Annotation table: mgs_annotation.tsv

### ARD analysis:

1. Select OTU/Gene table
2. Load the count table: evotar_ard_count_table.tsv
3. Load the annotation table: ard_annotation.tsv


## Models, targets et contrast files for each question:

For the analysis, select statistical analysis -> run differential. Load the target file and click on run analysis. Finally load the contrast file. For each analysis, a specific target and contrast file need to be loaded as follow:

### Evolution of ARDs and MGS in Beaujon A cohort before and after exposition to ceftriaxone (Paired analysis)

1. Load the target file: target_cohort_A.tsv, corresponding to the model : subject + ATB_exposure
2. Indicate level of analysis (except MGS for MGS analysis)
3. Click on run analysis
4. Load the contrast file: Contrasts_cohort_A.tsv


### Comparaison of ARDs and MGS between cohorts at hospital admission (cohortes A and C are grouped at t0 and Madrid cohort (D))

1. Load the target file: target_cohort_AC_D.tsv, corresponding to the model: subject + time
2. Indicate level of analysis (except MGS for MGS analysis)
3. Click on run analysis
4. Load the contrast file: Contrasts_cohort_AC_D.tsv

### Evolution of ARDs and MGS in Utrecht cohort (cohort E) between t0 and t1 (Paired analysis)

1. Load the target file: target_cohort_E.tsv, corresponding to the model: subject + time
2. Indicate level of analysis (except MGS for MGS analysis)
3. Click on run analysis
4. Load the contrast file: Contrasts_cohort_E.tsv


### Evolution of ARDs and MGS in Beaujon C cohort (stay at hospital without antibiotic exposure)

1. Load the target file: target_cohort_C.tsv, corresponding to the model: subject + time
2. Indicate level of analysis (except MGS for MGS analysis)
3. Click on run analysis
4. Load the contrast file: Contrasts_cohort_C.tsv

## Contact

If you have any comments, questions or suggestions, or need help to use SHAMAN, please contact authors [here](amine.ghozlane@pasteur.fr)


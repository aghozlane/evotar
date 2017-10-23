Count files loading :

MGS analysis:
Select MGS table type and load:
count table: evotar_mgs_count_table.tsv
Annotation table: ard_annotation.csv

ARD analysis:
Select OTU/Gene table and load:
count table: ard_annotation.tsv
Annotation table: ard_annotation.tsv


Models, targets et contrast files for each question:

Evolution of ARDs and MGS in Beaujon A cohort before and after exposition to ceftriaxone (Paired analysis)

Modele : subject + ATB_exposure
Target : target_cohort_A
Contrast : Contrasts_cohort_A


Comparaison of ARDs and MGS between cohorts at hospital admission (cohortes A and C are grouped at t0 and Madrid cohort (D))

Model: subject + time
Target: target_cohort_AC_D
Contrast : Contrasts_cohort_AC_D

Evolution of ARDs and MGS in Utrecht cohort (cohort E) between t0 and t1 (Paired analysis)

Model: subject + time
Target: target_cohort_E
Contrast : Contrasts_cohort_E


Evolution of ARDs and MGS in Beaujon C cohort (stay at hospital without antibiotic exposure)

Model: subject + time
Target: target_cohort_C
Contrast : Contrasts_cohort_C


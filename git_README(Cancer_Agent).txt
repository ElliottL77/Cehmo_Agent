* Final project for class, Biostatistics & Survival Analysis.
* Data given was about survival times comparing chemotherapy versus chemotherapy and a novel agent drug.
* Data was provided by the University of Massachusetts’s stat data website. Composed of a subset of patients who had an oropharynx cancer.
* 195 observations, 11 variables including the dependent variable.
o 100 in chemo alone
o 95 in chemo + chemo agent drug.
GenderTreatment (chemo vs. chemo + agent)	Grade (how different are patient’s normal cells to cancer cells)AgeDisabledCancer siteT_Stage (Stage of primary tumor)N_Stage (if cancer metastasized)Date the patient entered studyStatus (censored, died)Survival_time* Used SAS and the lifereg procedure with the log-log procedure. Significant variables:
o Disabled
o T_Stage
o N_stage
* Something of note, the treatment were not statistically significant (p = 0.2997)
* Ran the proportional hazard procedure (proc phreg) to find hazard ratio.
o Disabled – 2.3
o T_Stage – 1.2
* PH of N-stage was violated, appeared as 0.
* Chemotherapy plus the agent drug was found to not have a significant effect on survival time compared to chemotherapy alone.

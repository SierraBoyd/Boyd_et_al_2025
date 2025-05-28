This repository contains all source files and RMD files created for Boyd et al., 2025

Boyd_et_al_2025_RMDs_Raw_Data/Source_Data
  Contains 4 subfolder: 
    Action_Potential_Propagation_Raw_Data.csv: Contains all source files from the "Axon Tracking Analysis" and a meta file
    Neural_Network_Raw_Data.csv: Contains all source files from the "Network Analysis" and a meta file
    General_Activity_Raw_Data.csv: Contains all source files from the "Activity Analysis" and a meta file
    Cytotoxicity_Raw_Data.csv: Contains all source files for LDH and CellTiter-Blue Assays
    Longitudinal_Raw_Data.csv: Contains all source files for data utilized for the longitudinal analysis (ontogeny of electrical activity between weeks 2-10 for BrainSpheres)

Boyd_et_al_2025_RMDs_Raw_Data/RMDs
  Contains 11 RMD files:
    Action_Potential_Propagation_PreProcessing.Rmd: All preprocessing steps, exports a "Melt.csv" that will be used for Conc_Response.Rmd, Chemical_Washout.Rmd, and Coefficient of Variation.Rmd
                                                    Generates graphs for Figure 4C, Figure 5C, Supplemental Figure 1C, and Supplemental Figure 7 
    Action_Potential_Propagation_Conc_Response.Rmd: All Concentration-Response Modeling steps for all "Axon Tracking Analysis" data, Generates graphs for Figure 6C, Supplemental File 5, and the AC50 values in Supplemental File 6
    Neural_Network_PreProcessing.Rmd: All preprocessing steps, exports a "Melt.csv" that will be used for Conc_Response.Rmd, Chemical_Washout.Rmd, and Coefficient of Variation.Rmd
                                                    Generates graphs for Figure 4B, Figure 5B, Supplemental Figure 1B, and Supplemental Figure 6 
    Neural_Network_Conc_Response.Rmd: All Concentration-Response Modeling steps for all "Network Analysis" data, Generates graphs for Figure 6B, Supplemental File 4, and the AC50 values in Supplemental File 6
    General_Activity_PreProcessing.Rmd: All preprocessing steps, exports a "Melt.csv" that will be used for Conc_Response.Rmd, Chemical_Washout.Rmd, and Coefficient of Variation.Rmd
                                                    Generates graphs for Figure 4A, Figure 5A, Supplemental Figure 1A, and Supplemental Figure 5 
    General_Activity_Conc_Response.Rmd: : All Concentration-Response Modeling steps, for "Activity Analysis" data, Generates graphs for Figure 6A, Supplemental File 3, and the AC50 values in Supplemental File 6
    Chemical_Washout.Rmd: : Wilcoxin test for Chemical washout data, generates Supplemental File 7
    LDH_Conc_Response.Rmd: All Concentration-Response Modeling steps for all LDH data, generates Supplemental File 2
    CellTiter_Conc_Response.Rmd: All Concentration-Response Modeling steps for all CellTiter-Blue data, generates Supplemental File 1
    Coefficient_of_Variation.Rmd: Calculation of Coefficients of Variation for all recording types, generates data in table 2
    Longitudinal_Analysis.Rmd: All preprocessing steps to generate Supplemental Figure 4 
    

# Modal spaces

## Overview

This repository contains the experiment files, data, and analyses used to produce the paper, "Modal spaces as a foundation for high-level cognition" by Eli Hecht and Jonathan Phillips. 

## Directory Structure
This repository is organized as follows:

Modal spaces
* qualtricsStudies
   * Study 1a.docx
   * Study 1a.qsf
   * Study 1b.docx
   * Study 1b.qsf
   * Study 1c.docx
   * Study 1c.qsf
   * Study 2.docx
   * Study 2.qsf
   * Study 3.docx
   * Study 3.qsf
   * Study 4a.docx
   * Study 4a.qsf
   * Study 4b.docx
   * Study 4b.qsf
   * Study 4c.docx
   * Study 4c.qsf
   * Study 5.docx
   * Study 5.qsf
   * Study 6a.docx
   * Study 6a.qsf
   * Study 6b.docx
   * Study 6b.qsf
   * Study 6c.docx
   * Study 6c.qsf
   * Study 7.docx
   * Study 7.qsf
* data
   * Study 1a: pg1.csv
   * Study 1b: pg2.csv
   * Study 1c: pg3.csv
   * Study 2: ev.csv
   * Study 3: hadTo.csv
   * Study 4a: causal.csv
   * Study 4b: causal+counterfactual.csv
   * Study 4c: sufficiencyCounterfactual.csv
   * Study 5: blame.csv
   * Study 6a: altpg.csv
   * Study 6b: altev.csv
   * Study 6c: althadTo.csv
   * Study 7: htpg.csv
* manualCoding
   * texts_coding_1.csv (rater 1)
   * texts_coding_2.csv (rater 2)
   * texts_coding_3.csv (rater 3 settling cases of inter-rater disagreement)
* materials
   * contextsTable.csv
   * textsCodingKey.csv
   * actualActions.csv
* writeUp.Rmd
* writeUp.html
* lmerOutputs
   * pgPredictP.rda
   * pgPredictM.rda
   * pgPredictN.rda
   * pgNormInt.rda
   * pgNormM.rda
   * pgNormP.rda
   * altpgPredictP.rda
   * altpgPredictM.rda
   * altpgPredictN.rda
   * altpgNormInt.rda
   * altpgNormM.rda
   * altpgNormP.rda
* figs
   * fig1.jpg
   * fig2.jpg
   * fig3.jpg
   * fig4.jpg
   * fig5.jpg
   * fig6top.jpg
   * fig6bottomL.jpg
   * fig6bottomR.jpg
   * figS1.jpg
   * figS2.jpg
   * figS3.jpg
   * figS4.jpg


## Data and Analyses
The data folder contains anonymized unprocessed data downloaded from Qualtrics. All analyses are completed within writeUp.rmd based on these data as well as the materials and manual coding files, and the results are saved to the writeUp.html file. Figures are saved to the figs folder. To save processing time, the outputs from many of the linear effects models used in the analyses are stored in the lmerOutputs folder, allowing us to simply read in the results instead of recalculating them each time.

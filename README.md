# Modal spaces

## Overview

This repository contains the experiment files, data, and analyses used to produce the paper, "Modal spaces as a foundation for high-level cognition" by Eli Hecht and Jonathan Phillips. 

## Directory Structure
This repository is organized as follows:

Modal spaces
* writeUp
   * [writeUp.Rmd](/writeup/writeUP.Rmd)
   * [writeUp.html](/writeup/writeUP.html)
* qualtricsStudies
   * [Study 1a.docx](/qualtricsStudies/Study1a.docx)
   * [Study 1a.qsf](/qualtricsStudies/Study1a.qsf)
   * [Study 1b.docx](/qualtricsStudies/Study1b.docx)
   * [Study 1b.qsf](/qualtricsStudies/Study1b.qsf)
   * [Study 1c.docx](/qualtricsStudies/Study1c.docx)
   * [Study 1c.qsf](/qualtricsStudies/Study1c.qsf)
   * [Study 2.docx](/qualtricsStudies/Study2.docx)
   * [Study 2.qsf](/qualtricsStudies/Study2.qsf)
   * [Study 3.docx](/qualtricsStudies/Study3.docx)
   * [Study 3.qsf](/qualtricsStudies/Study3.qsf)
   * [Study 4.docx](/qualtricsStudies/Study4.docx)
   * [Study 4.qsf](/qualtricsStudies/Study4.qsf)
   * [Study 5a.docx](/qualtricsStudies/Study5a.docx)
   * [Study 5a.qsf](/qualtricsStudies/Study5a.qsf)
   * [Study 5b.docx](/qualtricsStudies/Study5b.docx)
   * [Study 5b.qsf](/qualtricsStudies/Study5b.qsf)
   * [Study 5c.docx](/qualtricsStudies/Study5c.docx)
   * [Study 5c.qsf](/qualtricsStudies/Study5c.qsf)
   * [Study 6.docx](/qualtricsStudies/Study6.docx)
   * [Study 6.qsf](/qualtricsStudies/Study6.qsf)
* data
   * Study 1a: [pg1.csv](/data/pg1.csv)
   * Study 1b: [pg2.csv](/data/pg2.csv)
   * Study 1c: [pg3.csv](/data/pg3.csv)
   * Study 2: [decision.csv](/data/decision.csv)
   * Study 3: [ev.csv](/data/ev.csv)
   * Study 4: [hadTo.csv](/data/hadTo.csv)
   * Study 5a: [causal.csv](/data/causal.csv)
   * Study 5b: [causal+counterfactual.csv](/data/causal+counterfactual.csv)
   * Study 5c: [sufficiencyCounterfactual.csv](/data/sufficiencyCounterfactual.csv)
   * Study 6: [blame.csv](/data/blame.csv)
* manualCoding
   * [texts_coding_rater1.csv](/manualCoding/texts_coding_rater1.csv) (rater 1)
   * [texts_coding_rater2.csv](/manualCoding/texts_coding_rater2.csv) (rater 2)
   * [texts_coding_3.csv](/manualCoding/texts_coding_rater3.csv) (rater 3 settling cases of inter-rater disagreement)
   * [pg_coded_final.csv](/manualCoding/pg_coded_final.csv) (compiled final ratings based on 3 raters)
* materials
   * [contextsTable.csv](/materials/contextsTable.csv)
   * [textsCodingKey.csv](/materials/textsCodingKey.csv)
   * [actualActions.csv](/materials/textsCodingKey.csv)
* computationOutputs (outputs of computation-intensive analyses)
   * [pgPredictP.rda](/computationOutputs/pgPredictP.rda)
   * [pgPredictM.rda](/computationOutputs/pgPredictM.rda)
   * [pgPredictN.rda](/computationOutputs/pgPredictN.rda)
   * [pgNormInt.rda](/computationOutputs/pgNormInt.rda)
   * [pgNormM.rda](/computationOutputs/pgNormM.rda)
   * [pgNormP.rda](/computationOutputs/pgNormP.rda)
   * [decisionResults.rda](/computationOutputs/decisionResults.rda)
* figs
   * [fig1.png](/figs/fig1.png)
   * [fig2.png](/figs/fig2.png)
   * [fig3.png](/figs/fig3.png)
   * [fig4.png](/figs/fig4.png)
   * [fig5.png](/figs/fig5.png)
   * [fig6.png](/figs/fig6.png)
   * [figS1.png](/figs/figS1.png)
   * [figS2.png](/figs/figS2.png)
   * [figS3.png](/figs/figS3.png)
   * [figS4.png](/figs/figS4.png)


## Data and Analyses
The data folder contains anonymized unprocessed data downloaded from Qualtrics. All analyses are completed within writeUp.rmd based on these data as well as the materials and manual coding files, and the results are saved to the writeUp.html file. Figures are saved to the figs folder. To save processing time, the outputs from many of the linear effects models used in the analyses are stored in the lmerOutputs folder, allowing us to simply read in the results instead of recalculating them each time.

# Undergraduate Fourth Year Dissertation

*Author:* Phoebe J.S. Santos


*Repository Description*:

This github contains the most relevant code used for my Fourth Year Dissertation. Exploratory code, experimental model building, and other multi-/uni-variate analyses are not included; however all statistical methods and figures within my main thesis and appendices are included within this code. 

Only one R '.Rmd' file is presented here with all relevant code included on it. Rough workflow for the Rmd file follows as: packages -> upload and wrangle data -> generalised additive model (GAM) building -> random cross-validation for model parameterisation -> spatially buffered leave-one-out cross-validation (LOOCV) -> AIC model comparisons & figures. There is additional code for figure building at the bottom of the Rmd (figures such as comprehensive tables and some raw data visualisations). 


> [!IMPORTANT] 
>The raw data is not included within this code due to it not belonging to this author. Please also note that this is not the main Rmd in which the actual outputs for models and figures was run - that was conducted in a separate Rmd then copied over & organised into this Rmd for public availability. As such, it is possible that some missorganisation occurred or object names were changed/lost in the transfer, or minor mistakes were made in copying over code. For anyone trying to reproduce the code, this may be important.
>Also important is that much of this code was adapted from other works, specifically the LOOCV; where possible I have tried to mention them specifically in the code but references to these authors are also made in my main thesis. These are adaptations, not copies-and-pastes so it is possible that some of the nuance from the original code was lost in my adaptation.

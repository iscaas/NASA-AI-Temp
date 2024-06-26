# Single-Agent Attention Actor-Critic (SA3C): A Novel Solution for Low-Thrust Spacecraft Trajectory Optimization
We provide the code repository for our paper. This repository includes the necessary code to replicate our experiments and utilize our SA3C-DRL model for spacecraft trajectory planning. By accessing the repository, researchers and practitioners can benefit from our approach to efficiently transfer spacecraft to GEO and CisLunar Transfer Points (NRHO and Patch-Point).


SA3C based Super-GTO to Cislunar Patchpoint transfer  | SA3C based Super-GTO to NRHO-L2 transfer
:-: | :-:
<![SA3C based S-GTO to PatchPoint transfer](/readmeplots/PP3dvid.gif) > | <![SA3C based S-GTO to NRHO transfer](/readmeplots/NRHO3dvid.gif) >




SA3C based GTO to GEO transfer  | SA3C based Super-GTO to GEO transfer
:-: | :-:
<![SA3C based GTO to GEO transfer](/readmeplots/GTO-GEO.gif) > | <![SA3C based S-GTO to GEO transfer](/readmeplots/SuperGTO-GEO.gif) >


## Files Description
Circular2body and CisLunar3body folders contains the code, plots and Final optimized weights. 
Circular2body folder contains the code for the following GEO targeted scenerios ie:
1. GTO-1 to GEO
2. GTO-2 to GEO
3. Super-GTO-1 to GEO

CisLunar3body folder contains the code for NRHO and Patch-point targeted scenerios.


    In these folder :
         - `config.py`: Contains the general configurations or initial parameters to run the code.
         - 'scenerios.py': Contains the Scenerios Specific configurations.
         - 'Spacecraft_Env.py' and 'enviornment.py': Contains general RL and Model specific enviornemnt functions.
         - 'SA3C_test.py' is the main code file to reproduce the results while using trained weights.
         - 'SA3C_train.py' is used to train the model from scratch. 


##Files Description
#Circular2body Folder
Contains code, plots, and final optimized weights for GEO-targeted scenarios:
1. GTO-1 to GEO    2. GTO-2 to GEO    3. Super-GTO-1 to GEO
#CisLunar3body Folder
Contains code for NRHO and Patch-point targeted scenarios.
#Common Files
- config.py: General configurations and initial parameters.
- scenerios.py: Scenario-specific configurations.
- Spacecraft_Env.py & enviornment.py: General RL and model-specific environment functions.
- SA3C_test.py: Main file to reproduce results using trained weights.
- SA3C_train.py: Train the model from scratch.
   

  


## Setting up Enviornment:
## Running the code:


## Methodology
<image src='/readmeplots/methodology.PNG' width=1000/>

## Results
<image src='/readmeplots/results.PNG' width=1000/>
  <div align="center">
<image src='/readmeplots/ablation studies.PNG' width=500/>
  </div>
  
SA3C based 2 body transfer  | SA3C based 3 body  transfer
:-: | :-:
<image src='/readmeplots/fig7.PNG' width=500/> | <image src='/readmeplots/NRHO3d.PNG' width=500/>
<image src='/readmeplots/2bodyscores.PNG' width=500/> | <image src='/readmeplots/3bodyscores.PNG' width=500/>
<image src='/readmeplots/2bodyresultsplots.PNG' width=500/> | <image src='/readmeplots/NRHOresultsplots.PNG' width=500/>

## Citation
If you find this work beneficial to your research or project, I kindly request that you cite it:
```

```

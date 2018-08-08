# ROM_Experiment
My own part of ROM experiment

## Load V-REP Scene
1. Change to V-REP directory
  * On Mac OS:
   
       `cd /Users/jack.lingheng.meng/GoogleDrive/Robot_Simulators/V-REP_PRO_EDU_V3_5_0_Mac`
  * On Windows OS:
  
       `cd C:\Program Files\V-REP3\V-REP_PRO_EDU\`

2. Launching V-REP with scene for ROM Exhibit
`vrep -gREMOTEAPISERVERSERVICE_20008  F:\ROM_Experiment\LAS-Scenes\livingArchitecture_ROM_exhibit.ttt`



## Visualizing with Tensorboard
1. Launching Tensorboard:

   `tensorboard --logdir=/Users/jack.lingheng.meng/GoogleDrive/Robot_Simulators/V-Rep-Python_Project_ASL/ROM_Experiment_results/LASAgentActorCritic/summary/run1`
2. Visualizing in Browser 

   `http://localhost:6006`

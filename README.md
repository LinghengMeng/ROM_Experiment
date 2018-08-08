# ROM_Experiment
My own part of ROM experiment

## Load V-REP Scene
1. Change to V-REP directory
   * On Mac OS: `cd /Users/jack.lingheng.meng/GoogleDrive/Robot_Simulators/V-REP_PRO_EDU_V3_5_0_Mac`
   * On Windows OS:  `cd C:\Program Files\V-REP3\V-REP_PRO_EDU\`
2. Launching V-REP with scene for ROM Exhibit

   `vrep -gREMOTEAPISERVERSERVICE_19997  F:\ROM_Experiment\LAS-Scenes\livingArchitecture_ROM_exhibit.ttt`

## Run Python Script

  1. Command: `python Interaction_LASAgent_and_Visitor_and_Env.py`
  
  2. Annoconda Spyder: run script `Interaction_LASAgent_and_Visitor_and_Env.py`

## Visualizing with Tensorboard
1. Launching Tensorboard:
   * Mac:
   `tensorboard --logdir=/Users/jack.lingheng.meng/GoogleDrive/Robot_Simulators/V-Rep-Python_Project_ASL/ROM_Experiment_results/LASAgentActorCritic/summary/run1`
   * Windows Conda Prompt:
   `tensorboard --logdir=F:\ROM_Experiment_results/LASAgentActorCritic/summary/run1`
2. Visualizing in Browser 

   `http://localhost:6006`

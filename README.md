# Modeling and Control of a Vertical Hopping Robot
This project was my (Bradley Kwan) Master's thesis at California Polytechnic State University - San Luis Obispo. 
The goal of the thesis is to develop an accurate model of a vertical hopping robot within Simulink, allowing for controller development and comparison to a physical prototype.

## MATLAB Files
The following MATLAB files are used to run the Stateflow and Simscape simulations.

    - HopRobot_Stateflow.mlx: MATLAB live script used to simulate the Stateflow Simulink model. 

## Simulink Files
The following Simulink files model the dynamics of the hopping robot constrained to a vertical slider.

-HR_Stateflow_Control.slx: Simulink file which uses Stateflow to run two Simulink models in tandem with each other.
Stateflow handles the transitions between the two models based on the state of the system.

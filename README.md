# time-efficient-improve-for-walking-robot
THE FILE CONSIST:
1) MIQP is consiting all the simulation data for conventional walking simulation
	a)sim_with_qp -> is the folder that consists of the simulation result including the simulation result 

2) SL is the folder consisting the simulation data for the walking robot that using supervise trained joint model
	a)trained_joint_model_and_simulation_result -> all the trained joint model and simulation result are included

*notes: for comparing between the conventional result and the supervise learning result, the file for epcoch number 5000 is refer.

3) raw_data_0623 is the folder consist of the joint data taht extract from the raw_data_collected with the script of preprocess.py, it is then used to train the joint models with the script Train_Joint_Model.py

4) raw_data_collected is a folder that consist of the raw data from the walking simulation, which were used to preprocess for extracting the joint dataset with preprocess.py and store in raw_data_0623
 

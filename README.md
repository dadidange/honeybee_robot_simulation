# honeybee_robot_simulation

## WHAT IS IT?

This model provides a simulation of the honeybee experiment developed by T. Schmickl et al in their paper ``Social Intergrating Robots Suggest Mitigation Strategies for Ecosystem Decay'' (2021).
This model was developed for the the Seminar 'Cyber Physical Systems' (2021/22) at 'University zu Lübeck'. 

## HOW IT WORKS

Two static agents (combined actuator sensor units or CASUs) emit `attraction' which is based on the ODEs (Eqs. B1a,b) developed by Schmickl. et al. 
In general, the bees get attracted to the attraction but due to some noise added, they can walk around randomly as well. 

## HOW TO USE IT

To start, press 'SETUP' for initialization and 'go' for actually running the simulation. Using the 'Experiment' drop-down, a specific experiment can be chosen. 
Since logging is difficult for the web-application, this model can probably not be used there. 
For logging on your own computer, change the file first.

## THINGS TO TRY and EXTENDING THE MODEL
Try different parameters for default parameters (e.g. num_bees, temperatures, vibration or airflow. Try different setups for diffusion rate or evaporation as well.) Additionally, other CASUs can be implemented as well.

## CREDITS AND REFERENCES

*Original Paper*:
Schmickl T, Szopek M, Mondada F, Mills R, Stefanec M, Hofstadler DN, Lazic D, Barmak R, Bonnet F and Zahadat P (2021) Social Integrating Robots Suggest Mitigation Strategies for Ecosystem Decay. Front. Bioeng. Biotechnol. 9:612605. doi: 10.3389/fbioe.2021.612605
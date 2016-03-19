# neural_network_fot
A simple multi layer perceptron demo for the Livable Future Park in Fót, Hungary in CiCode language.

I want to create an MLP demo for our renewable park's SCADA system. 
The environment is CitecSCADA 2015 (v7.50) by Schneider Electric.

First I will create a 4 layered neural network with total 44 neurons.
The learning method will be backpropagation (backward propagation of errors).

When this neural system is able to learn I will use it to forecast the photovoltaic generation of our PV panels, based on the exact moment of time, the PV panel's temperature, the ambient temperature and the global radiation.

The mentioned weather data is available real-time in our scada system. The neural network will learn the correlation between the weather and time by the last 3 days (based on weighted averages) in the first and second layer. In the 3rd and 4th layer the network will learn the correlation between the weather data and the output power based on the last 30 day's weighted data.

2016.03.19. Budapest, Hungary
Gergely Sasvári

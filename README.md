# Machine-Learning-in-Traffic-Classification-of-SDN

##Problem Definition 

the calssification of traffic flows in today's IP network has become an important research area with the adopation of machine learning techniques and Software Defined Network (SDN) Principles. Traditional methodologies including identifying traffic based on port number and payload inspection are not effective due to the dynamic and encrypted nature of current traffic. This project will attempt to utilize Supervised and Unsupervised ML Algorithms to classify flows based on packet and Byte information.

##Process 

*Build Topology
	Setup virtualBox with Host, Switch, Controller VM
	Create Internal network as underlay network
	Configure overlay network

*Simulation Traffic Flows
	Use simulation tools to send various traffic flows between hosts 
	Modify controller scripts to output required data

*Collect Training Data
	Write scripts to collect output of controller monotoring application

*Train Models
	Using Jupyter Notebook, train and test supervised and unsupervised Machine Learning Models.

*Use Models Real Time
	Usung Models created in Notebook, Classify traffic real time from data collected from Ryu App.

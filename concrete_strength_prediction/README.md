# Concrete Strength Prediction
This project predict compressive strength of High perfomance concrete and Ultra high perfomance concrete, It's a project made for my graduation in Civil Engineering at 
Federal University of Ceará. 

*CONTEXT*
As the advances in concrete production are accelerating it makes possible to make more resistant concretes.
High Performance Concrete (HPC) are already made by the main concrete companies and this also expected for Ultra High Perfomance Concrete (UHPC).
However, their dosing methods didn't follow the process of development, most of them use plots and tables with limited capacity to predict new concrete mixtures.
This way it makes necessary new advanced tools capable to analyse the influence of materials and predict the concrete behaviour. For this task we have great potencial on 
machine learning models as they can be applied on the most complex problems based on colected data.
This project developed compressive strength prediction models for both types of concrete, HPC and UHPC, using a dataset upgraded by that research from studies published.

*WHAT THIS PROJECT DO*
The first analyses consider the datasets merged to see how similar those concretes could be, knowing that they use the same materials on their mixtures, but from that we
see that they actually use different quantities from each material and have different aditions like quartz and limestone powder, also UHPC don't use coarse aggregate and
can have heat treatment. From this analyses it's decided to work with both data separately.
To create the predicting tool four models were tested, Linear Regression, Regression Tree, Random Forest and Artificial Neural Network (ANN), all using cross-validation
By the end ANN had the best metrics and was tested with partial dependece to check how the model sees which material influence, if it's right according to researchers.
The model for both concretes had good performance and 
adequate interpretation. 

*WHY IT IS USEFUL*
It can be used to predict compressive strength by the materials quantities used on the mixture, having good accurancy which helps to save money and materials on tests.

*FULL TEXT IN PORTUGUESE:* http://www.repositorio.ufc.br/handle/riufc/68403


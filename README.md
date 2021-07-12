# Whatsupp

Here I write about my learning journey.
I am a IT student at the University of Stuttgart, and I have background in Electrical Engineering. I have a passion in working with number, especially, in a energy management system. 
The idea sparked in my internship in 2016 at a paperfactory in Thailand, I was assigned a design task for a power switching system. I thought to myself "why dont we make it smarter", then I follow the idea, and step by step, I did what I am dreaming of. I have been learning software engineering and AI to enlarge my knowledge and better my skills. 

My interest: time series forecasting, competitive programming and MLOps.

Here are some projects that I am sharing:

# [Feature Ranking](https://github.com/FrancisDinh/Feature_ranking)
There are 400 samples from 10 sensors, and they are classified in two classes -1 and 1. This task required to rank the feature importance. This report represents three types of approaches: filter, tree-based and wrapper method; additionally, a soft SVM is used to rank the features based on their coefficients. The main problem of with the dataset is testing the ranked features. In order to understand the ranking models and to pick the best performed one, one final (neutral) model should try to predict the classes of sensors based only on the ranked sensors. Therefore, once there are the ranked sensors, it is very difficult to argue that the ranking is totally correct. In this experiment, we also try to test the ranked sensors by (1) use wrapper method to test the ranked feature of tree-based and soft SVM model and (2) using Linear Classification to predict based on the ranked features. In conclusion, sensor 8 is more important than others in classification task.

# [Energy demand forecasting](https://github.com/FrancisDinh/Energy-forecasting-in-EMSs)
Continue to realize a real-life scenario of a energy management system, where it has a demand forecasting module.
Energy Management System (EMS) is emerging as a solution for the power grid management, which
is indicated by the profit, stability, and reliability to its end users. Load forecasting is a component of
an EMS, and it is vital to foresee the future demand to generate a proper schedule for a microgrid. A
load forecasting study should cover all types of loads: commercial buildings and households, which
has been incompletely studied in other papers. Since 2018, with the improvement in computing
power, Deep Learning (DL) models have caught attention in many studies, and shown their potential
over the traditional method Auto Regression Moving Average (ARIMA) in solving forecasting
problems. In the DL branch, Recurrent Neural Network (RNN) is the type of model having memory,
which is designed to estimate future values on history data. This thesis studies the application of
RNN in forecasting energy consumption of both load types and implements a service that forecasts
demand focusing on commercial buildings. We experiment with six different RNN-based models
on two sets of data, commercial buildings in 2004 in San Francisco and households between 2011
to 2014 in London. The performance of the RNN family significantly exceeds ARIMA in accuracy
and processing time. In two study cases, the reported error of the best performer in RNN-based
models is **48%** and **23%** lower than ARIMA. The Forecasting service for commercial buildings is
then implemented as a restful Application Programming Interface (API) for further deployment in
an EMS.

# [Energy management system (EMS)](https://github.com/FrancisDinh/Smart-Energy-Project)
This project gives information on existing functionality of the mi-
crogrid, challenges involved, features that can be added on the existing
architecture. Microgrid works as a local energy provider for domestic
buildings to reduce energy expenses and gas emissions by utilizing dis-
tributed energy resources (DERs). The rapid advances in computing
and communication capabilities enable the concept smart buildings be-
come possible. Most energy-consuming household tasks do not need to
be performed at specific times but rather within a preferred time. If these
types of tasks can be coordinated among multiple homes so that they do
not all occur at the same time yet still satisfy customers requirement,
the energy cost and power peak demand could be reduced.

# [Smart office with AI planning](https://github.com/FrancisDinh/Smart-Office-with-Pi)
With the emergence of IoT in every corner of the modern life, the communication
between devices plays an important role in transforming a traditional building
to a smart building, which can operate stably standalone and interact with
human and environment. According to Green Building Council Australia (2013),
a smart commercial building consumes 66% less electricity and produces 62%
fewer greenhouse gas than a traditional one.

The heart of a smart building is data, which is harvested via sensors and end
devices, then transferred to the solution by utilizing devices to satisfy specific
constraints. The goal of this project is to design and implement a smart office
using a Raspberry Pi manipulating a lighting system, air conditioner, and a door
via a relays with the information from Grove Pi sensors. The model shall optimize
energy efficiency and ensure the safety, privacy, comfort of its occupants.

# [Tensorflow developer](https://github.com/FrancisDinh/Tensorflow_report)
- Sign language MNIST: multiclass classification CNN, accuracy **91%**
- Horse - human classification: upgrade vanilla CNN with with data
augmentation, accuracy **71%**, upgrade with transfer learning of
VGG Net, accuracy **99%**
- IMDB review classification: tokenization, padding and word
embedding, MLP, Conv1D, accuracy **82%**
- Text generation: bidirectional LSTM, generate poem based on
Shakespeare's Sonnets, smooth text and limited meaning

# [Stainless Steel Price forecasting](https://colab.research.google.com/drive/1EqCoCDg4hczm6OBhOmU5R_USfxQAESwJ?usp=sharing)
[Cont](https://colab.research.google.com/drive/1qLCoi6uWw_zuvLaMmqHtgDfiOh2c-VnY?usp=sharing)

It is a challenge that came across my face, and I decided to take it. The question is to forecast the price of stainless steel in the next 3-6 months using statistical, ML and DL models. Models are evaluated by MAPE and Directional Symmetry. During the process, it was figured out that Nicke, Baltic dry index and CLI of China also play important roles in steel price prediction. Trying with univariate models: ARIMA, Linear Regression and CNN-LSTM and multivariate VAR, Linear Regression and CNN-LSTM. Results was not good for multivariate CNN-LST (MAPE 33%) while univariate CNN-LSTM (MAPE 4%). Linear Regression is unexpectedly peforms quite well.

# [Database analysis](https://github.com/FrancisDinh/Data_Analysis)
Database analysis: normalize 3NF standard, write backup job
schedule with T-SQL, write analysis procedure




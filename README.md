# NASA-SpaceAppsProjectrepo
Our code base for the competition. 
This repo consists of 2 notebooks:
One notebook for data analysis(seismic analysis.ipynb) and the other for executing our idea for the competition(NueralnetworkLunar.ipynb).
Apart from that there is a word file explaining the data analysis part, I'll add a word file for the Nueralnetwork file as well if i get time before the deadline.
There are some images of the plots of the data.

The idea behind the project is to have a event point in every lunar data CSV provided in the challenge resources section, and label the data points according to the time they are away from the event point (in multiples of 3).
This data is transferred to the nueral network where the X is the data points of a particular group(eg: data points that are 3 hours aways from moon-quake) and Y is the time it is away from the event (eg: 3).

These X and Y values will be used to train the nueral network consisting of LSTM layers. This nueral network may be used to predict the amount of hours to an event (like moon-quake) based on live data. 

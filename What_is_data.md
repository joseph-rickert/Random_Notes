
### What is Data?
There wouldn't be statistics or data science without data. But what exactly is data? Even among statisticians the  notion is mostly left undefined. R.A. Fisher begins his influential *Statistical Methods for Research Workers* by defining statistics:

> The science of statistics is esentially a branch of Applied Mathematics, and may be regarded as mathematics applied to observarional data. <sup>1</sup>

and shows how to go about analyzing data without any elaboration as to what may be considered as data. Nevertheless, after being shown a few data files people mostly get the general idea, and I suspect that many data scientists,  data analysts, and even statisticians lead productive careers without ever seriously examining the issue. So let's start at the beginning. Suppose you are geologist and you find an interesting rock in your favorite quarry. Is the rock data? Not really.

If your randomly selected the rock from some section of the of the quarry then you could consider the rock to be a random selection of the population of rocks from that section of the quarry, and if you randomly selected a bunch or rocks you might think of this collection as a random sample. But, I don't think many statisticians would say that you have any data, you still just have rocks.

You might begin the process of manufacturing data by writing down things like the name and location of the quarry, the time and manner of collection, etc.  And if you are interested in the rocks, you can write all of this down and still not have any data. At best, you have some *meta-data* information about the providence of the rocks and information about your research methodology that will be useful in talking about the data that you haven't yet collected.

Not until you start examining the features of the rocks themselves, their color, size, chemical composition etc. would you begin to gather data. The more sophisticated questions you ask about the rocks the further you get away from the rocks themselves. For example, you might be interested undertaking a Mössbauer spectroscopy analysis to determine the valence state of iron in the minerals of your rocks and identifying the various iron oxides. <sup>2</sup>. Now, for each rock, you have tables of observed features (color and shape and lists of detected elements and minerals, for example), and measurements (simple measurements like weight, and complicated measurements such as spectral peaks that depend on sophisticated equipment and measurement techniques). Additionally, for each rock you have lists of laboratory equipment, and assumptions and mathematical models that needed to make the measurements.

Now you have data. Anyone can see that. But what you identify as data in the paper you write will depends on what scientific questions you choose to investigate. Ideally, you would have asked these questions and identified what you mean by data before you even picked up you first rock, but things don't always work this way. Someone totally unaware of you original intentions could find your final data file, see that there are features recorded for hundreds of samples, recognize the regularities in rows and columns of numbers and categorical features and believe that they have data. But do they?

Some statistical purists may say no: they do not. Without deciding on the scientific questions to be answered, methods of analysis, and criteria for testing hypothesis they do not have data, or at least they do not have anything that may used to make objective statements about the world. Until the age of computers, the ubiquity of data sets and the ease of "crunching" numbers this may have been a reasonable, but curious position to hold. Reasonable, because it emphasizes the integrity of the scientific process, curious because it purports to build objective knowledge on intentions and subjectivity.   

In our data driven world it is common to hear people advocate to "to let the data speak for itself". However as Arturo Peres Reverte ovserves in his novel *The Club Dumas*:

>. . . there are no innocent readers anymore. Each overlays the text with his own perverse view.  A reader is the total of all he’s read, in addition to the films and television he’s seen. To the information supplied by the author he’ll always add his own.

Just so, there are no innocent statisticians and data scientists. Not only do they all bring to their data the residue of every data set they have ever seen, and every analysis they have ever done, they at least partially synthesize their data from their intentions, decisions and assumptions.

Today, in the age of data science, given reasonable meta-data describing the provenance of a data set most data scientists would feel quite comfortable drawing conclusions from found data. The only real (mostly unstated) reservation about doing so would be the availability of similar data. Many data scientists are apparently comfortable about drawing conclusions from found data sets if they are sure that they can find more just like what they have. The main idea is that if algorithms can be trained on a data set and then can be used to make accurate predictions from new data not used in the training process, then they are indeed learning something useful about the world.

So, I offer this definition:

Data is any organized collection of categorical and quantitive information that can be interpreted as observations about some collection of things which can be used to make predictions about similar things.


### Information
We have seen that, for all practical purposes, existential questions about data are regularly side stepped and replaced with operational practicalities. 

<sup>1</sup> R.A. Fisher, Statistical Methods for Research Workers, (4th ed.) Oliver and Boyd, Edinburgh 1932

<sup>2</sup> https://serc.carleton.edu/research_education/geochemsheets/techniques/mossbauer.html
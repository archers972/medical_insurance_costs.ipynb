
From CodeCademy Data Scientist Inference Carreer Path this assignment ( Portfolio Project: U.S. Medical Insurance) explores the data from a US insurance company. With the methods .info() and .describe() we explore the dataset. I used. seaborn.pairplo() method to further get an impression. 
To explore whether genders are equally distributed among age groups a histplot was included. 
The amount of children among genders did not seem differ although the age groups show a curve for mean of children, as expected. The following histplot explores the range for amount of children.
Next I wanted to explore whether the 4 regions show us gender specific differences for smoking . It seems this is the case. The following graph explores the same regions for BMI differences between genders. These differences may cause biases in interpretations.

As charges are the main force for insurance companies to reflect risk behaviour , the next graph is showing exactly this for smoking. 
We go on to look at whether BMI induces more charges. For smokers an interesting observation is made, at BMI 30 charges jump, but not for non-smokers 

Lastly , charges corrected for gender , smoking status and bmi are combined for their binary subgroups and plotted for age. It gives us an informative idea that charges are really related to risk behaviour and age. I think this graph is very informative. 

The next step would be to make a predictive model to calculate the premium an insurer is to impose on the policyholders

I have yet to explore whether the different regions get charged differently when correcting for BMI , smoking and perhaps gender . And whether the amount of children in the household plays a role in the total charges. This will done later . Please feel free to comment and how i can improve my coding and graphs , I am having little coding experience, this is my first project.

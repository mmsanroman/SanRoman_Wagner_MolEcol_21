# SanRoman_Wagner_MolEcol_21


## Random viable networks ("species")

The different folders contain the random viable networks ('species') used in this study. 

To create the networks, we used a Markov Chain Monte Carlo sampling method which allowed us to efficiently sample a large space of metabolic reactions - the pan-metabolism. We used a previously assembled pan-metabolic network comprising 7222 reactions which can be obtained from San Roman & Wagner, 2018. 

Each separate text file contains the description of a random viable network. A network is described by a sequence of zeros ('0') and ones ('1'), with a total of 7222 elements (as many elements as number of reactions in the pan-metabolism). A '1' at position i indicates that the pan-metabolic reaction listed in position i is included in the random viable network.

Random viable networks are grouped according to their metabolic complexity, i.e. the number of reactions included in the metabolic network. We worked with species of metabolic complexity 'r-1000', 'r-500', 'r', 'r+500' and 'r+1000' which are found in the Data folder, in the subfolders metabolic_complexity_r-1000_1583reactions, metabolic_complexity_r-500_2083reactions, metabolic_complexity_r_2583reactions, metabolic_complexity_r+500_3083reactions and metabolic_complexity_r+1000_3583reactions, respectively. In addition, for metabolic complexity 'r' we created random viable networks which were selected to be viable on different carbon sources. We include these networks in folders 'Data/metabolic_complexity_r_2583reactions/CARBON-SOURCE_selected_metabNets' where CARBON-SOURCE is one of the carbon sources used in this work, that is, acetate, alanine, glucose, pyruvate and serine. 






 I am working on  glass forming temperature.I have performed exploratory data analysis on the dataset followed by distributional analysis of individual features.Finally I am performing regression analysis 

Metallic Glass Descriptors:

	Relevant papers:
		There is no paper published on this data set at the present time.  The data was assembled
		primarily by Vanessa Nilsen under the guidance of Prof. Dane Morgan at UW Madison
		 (ddmorgan@wisc.edu).
		A previous study of reduced glass transition temperature as a GFA descriptor can be found in reference [5]:
		https://www.sciencedirect.com/science/article/pii/S0022309300000648
		
	X features:
		The metallic glass dataset gives two columns with information about the material
		Composition. The first is the overall composition, and the second is the highest
		Composition element. The columns from four to the end are the MAGPIE features that
		have been generated from the material composition column and give values such as
		properties averaged over the material composition as well as features that are only for 
		the majority element in each alloy [3]. The majority element features are labelled as 
		"site1".
    
    Y property:
		The reduced glass transition temperature (Trg) has historically been used as a rough 
		predictor for Glass Forming Ability (GFA). By making a model to predict Trg for an 
		arbitrary alloy, it could be possible to use these values to estimate GFA directly, or as 
		input for another model to then predict GFA.
    

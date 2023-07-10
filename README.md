# Biodiversity Data Analysis Project

# Project overview
* This project analyses biodiversity data observed at various national park sites.
* This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.
* It was found that bird and mammal species are likely to become endangered
* It was also found that Yellowstone National Park has good biodiversity.
* The Python modules used were matplotlib, scipy, pandas, and numpy.

# Project Goals
Objective:

**Understanding characteristics about the species and their conservations status, and those species and their relationship to the National Parks.**

Questions:
* What is the distribution of conservation status for species?
* Are certain types of species more likely to be endangered?
* Are the differences between species and their conservation status significant?
* Which animal is most prevalent and what is their distribution amongst parks?
* How is the distribution of conservation status in birds?
* How is the distribution of conservation status in birds of prey?
* How is the distribution of birds of prey in each national park?

# Data cleaning and understanding
After importing the module and loading the datasets from the two CSV files, we will clean and understand the data.
* Replacement of null values to make the data easy to understand.
* Reviewing the data:
    * There are about 5541 species.
    * Species categories include Mammals, Birds, Reptiles, Amphibians, Fish, Vascular Plants, and Non-vascular Plants.
    * Species conservation status includes No Intervention, Species of Concern, Endangered, Threatened, and In Recovery.
    * The observed National Parks are Great Smoky Mountains National Park, Yosemite National Park, Bryce National Park, and Yellowstone National Park.

# Analysis
The data was analyzed by answering the questions that had been asked. Some conclusions were obtained, which are presented below.

* Distribution of conservation status: Species of Concern has the highest conservation status with 151 species. In addition, 15 species are categorized as Endangered, and ten are categorized as threatened.
  
![conservationstatusbyspecies](https://github.com/al1fandi/Biodiversity_Project/blob/main/images/Conservation%20Status%20by%20Species-Nointervention.png?raw=true)


* Certain types of endangered species: Species in the Mammal category are potentially more endangered than Birds and other species.

![percentageprotected](https://github.com/al1fandi/Biodiversity_Project/blob/main/images/Percentage%20of%20Protected%20Species.png?raw=true)


* Statistical significant: Based on the p-value, it was found that Mammals are more endangered than Reptiles.   


* Species distribution in National Parks: Various terrestrial, aquatic, and semi-aquatic animals inhabit Yellowstone National Park. This finding indicates that Yellowstone National Park has good biodiversity, especially animals.

![animaldistributioninnationalpark](https://github.com/al1fandi/Biodiversity_Project/blob/main/images/Animal%20Species%20Distribution%20in%20National%20Park2.png?raw=true) 

* Distribution of conservation status in birds: Many birds are still not protected. We've got 72 Species of Concern, 3 In Recovery, and 4 Endangered species.
  
![conservationstatusofbird](https://github.com/al1fandi/Biodiversity_Project/blob/main/images/Distribution%20of%20Conservation%20Status%20in%20Birds.png?raw=true)
  
* Distribution of conservation status in birds of prey: No birds of prey were found to be Endangered. Most birds of prey are still unprotected, with 10 Species of Concern and one species In Recovery.

![conservationstatusofbirdofprey](https://github.com/al1fandi/Biodiversity_Project/blob/main/images/Distribution%20of%20Conservation%20Status%20in%20Birds%20of%20Prey.png?raw=true)

* Bird of prey distribution in National Parks: Birds of prey are common in Yellowstone National Park.

![birdofpreydistribution](https://github.com/al1fandi/Biodiversity_Project/blob/main/images/Bird%20of%20Prey%20Distribution%20in%20National%20Park.png?raw=true)


# Conclusions
* Most are Species of Concern, but a valuable finding is that of the 25 threatened species, 15 are Endangered.
* Mammal and Bird species are more likely to be Endangered.
* Based on statistical tests, Birds are more likely to be Endangered than Reptiles.
* Birds are the most common animals found. The most extensive distribution of animals is in Yellowstone National Park.
* Many birds are still not protected. There are 79 birds with Protected status, 4 of which are Endangered.
* No birds of prey are classified as Endangered. There are 11 protected species and 23 unprotected species.
* Birds of prey are most common in Yellowstone National Park.
* You can access the code in this **[LINK](https://github.com/al1fandi/Biodiversity_Project/blob/3bccf3ed50a5507f9d67683768678daab54e4d43/code/Biodiversity%20Data%20Analysis%20Project.ipynb)**

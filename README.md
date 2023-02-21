# band-gap-ml-project
This is a repository containing the files to my final project in my Machine Learning for Physicists Class in the Fall of 2020. Here I used two different machine learning models in order to model the band-gap of various binary molecules. 


Data Collection and Calculation:
- Using the Pymatgen (Python Materials Genomics) library, the possible band-gaps for various molecules was obtained using particularly the MPRester class's query method, to obtain the Band-Gaps for Group III-V, Group II-VI, Group I-VII and Group IV-VI binary semiconductors.
- Then, using the molecular formula for each, I calculated using pym, the number of each element, the electronegativity difference between the two atoms, the atomic fraction, the molecular weight and the group number of the cation. These values serve as the features for the two machine learning models.


(INCOMPLETE)


### Task



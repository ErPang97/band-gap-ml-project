# band-gap-ml-project
This is a repository containing the files to my final project in my Machine Learning for Physicists Class in the Fall of 2020. Here I used two different machine learning models in order to model the band-gap of various binary molecules. 


Data Collection and Calculation:
- Using the Pymatgen (Python Materials Genomics) library, the possible band-gaps for various molecules was obtained using particularly the MPRester class's query method, to obtain the Band-Gaps for Group III-V, Group II-VI, Group I-VII and Group IV-VI binary semiconductors.
- Then, using the molecular formula for each, I calculated using pym, the number of each element, the electronegativity difference between the two atoms, the atomic fraction, the molecular weight and the group number of the cation. These values serve as the features for the two machine learning models.

Data Pre-Processing:
- The query's from above were stored in Pandas dataframes. To remove unrealistic molecules, I filtered for molecules that have weights less than 1000 amu, as well as for electronegativity differnces no greater than 10.


(INCOMPLETE)


### Task



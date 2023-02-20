Read me: - 

1. The Dataset folder contains all protein sequences used for the experiment.
2. Procedure:-
   a. load the dataset 
   b. feature extraction :

		Solvent accessibility: "https://github.com/psipred/psipred" 
		Reference:- McGuffin, Liam J., Kevin Bryson, and David T. Jones. "The PSIPRED protein structure prediction server." Bioinformatics 16.4 (2000): 404-405.

            Physicochemical properties are retrieved from Meiler's study 
		Reference:- Generation and evaluation of dimension-reduced amino acid parameter representations by artificial neural networks 

            PSSM and PSFM are computed by DeepMSA: "https://github.com/kad-ecoli/hhsuite2"
		Reference:- [38]	Zhang, Chengxin, et al. "DeepMSA: constructing deep multiple sequence alignment to improve contact prediction and fold-recognition for distant-homology proteins." Bioinformatics 36.7 (2020): 2105-2112.

3. Model training and testing: - 
    a. Training : open command prompt and move to "My_Project\Training\dist" and run training.exe
    b. Testing : open command prompt and move to "My_Project\Testing\dist" and run prediction.exe
                    Sample input : Choose the target-id from test_set eg:- T0963-D3

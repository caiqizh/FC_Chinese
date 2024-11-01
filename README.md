# FC_Chinese

## For the adversarial dataset:
- ```original_symmetric_250_pairs``` contains the claim-evidence pairs selected from CHEF for revision.
- ```generated_symmetric_250_pairs``` contains the claim-evidence pairs revised by ChatGPT and also verified by humans.
- ```without_permutation_500_pairs``` is the combination of the above two.
- ```with_permutation_500_pairs``` is created using the symmetric setting described in our paper.
- ```mixed_symmetric_1000_pairs``` represents the entire dataset.

Each JSON file has a corresponding pickle file that includes the relevant labels. 

# tc-challenge
AI Tinkerers Ottawa submission for the challenge [here](https://github.com/EricFillion/tc-challenge). `finetune_deberta_submission.ipynb` has the code and `requirements.txt` should contain everything needed to replicate it.

## Results
total: 2388 correct: 2187 accuracy: 91.583%

## Note on Reproducibility
I made the mistake of not specifying a seed, so a fresh run will likely have slightly different results (although I expect it should still be close). I do have the weights saved for the run that generated this notebook if needed.

## Update - 2024/05/02
I added a notebook that contains some partially cleaned up code to show the Hyperparameter Search I did with Ray. There's also an associated `requirements-ray.txt` that should install the necessary dependencies. 

# deep-learning-challenge

## Notes
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Outputs
First Attempt (Starter_Code.ipynb):  \
    1. Preprocessing:  \
        a. Drop the EIN and NAME columns \
        b. Target variable: IS_SUCCESSFUL \
    2. Compiling, Training and Evaluating:  \
        a. Hidden Layer 1: 80 neurons \
        b. Hidden Layer 2: 30  neurons \
        c. Epochs: 100 \
    3. Accuracy: 72.93 \

Optimization Attempt 1 (AlphabetSoupCharity_Optimization1.ipynb):  \
    1. Preprocessing: Same as initial model \
    2. Compiling, Training and Evaluating:   \
        a. Hidden Layer 1: 100 neurons \
        b. Hidden Layer 2: 50 neurons \
        c. Epochs: 120 \
    3. Accuracy: 73.01

Optimization Attempt 2 (AlphabetSoupCharity_Optimization2.ipynb):  \
    1. Preprocessing: Same as initial model \
    2. Compiling, Training and Evaluating:   \
        a. Hidden Layer 1: 100 neurons \
        b. Hidden Layer 2: 50 neurons \
        c. Epochs: 150 \
    3. Accuracy: 73.11 

Optimization Attempt 3 (AlphabetSoupCharity_Optimization3.ipynb):  \
    1. Preprocessing: Same as initial model \
    2. Compiling, Training and Evaluating:   \
        a. Hidden Layer 1: 100 neurons \
        b. Hidden Layer 2: 45 neurons \
        c. Epochs: 170 \
    3. Accuracy: 72.91 

## Summary 
We did not accomplish the 75% accuracy target after multiple optimization attempts. The highest accuracy this model attained was 73.11% at the second optimization. We ran through different iterations for the hidden layers of neurons and epochs. Further enhancements could be made by continuing to iteratate through different compiling/training/evaluating steps. 

### Resources
Class resources and Chat GPt \
Starter code: https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/Starter_Code.zip
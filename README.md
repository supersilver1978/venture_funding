# venture_funding

This program relies on machine learning and neural networks to help venture funds evaluate potential investments in companies. The binary classifier model should predict whether an applicant will become successful and will be evaluated based on accuracy and loss.

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, Numpy, Pathlib, Sklearn, Keras, Tensorflow
- **Framework:** JupyterLab, can also use VS Code
- **Operating Systems:** Microsoft Windows

---

## *Installation Guide*

****
- **1:** Install Jupyter Labs and run it from the terminal. Make sure that you make sure you have an up-to-date version of Python
 [Install and run JupyterLab:](https://jupyter.org/install)
- **2:** Copy URL of this repo
- **3:** Clone folder to this repo and open in jupyter labs
- **4:** Ensure that you have the imports correctly identified to download

---

## *Usage*

**Jupyter Lab**
- Running the code can be done in one of two ways:
    1. You can click the "play" button at the very top of the notebook.
    2. You can click shift + enter on each block of code to run each batch of code as you go through it. 
<img width="350" alt="run preview" src=https://github.com/supersilver1978/bitcoin_arbitrage/blob/main/Resources/run.png>

## *Final Product*

The model utilizes 116 inputs to train the model. We have attempted to manipulate 3 different variables to optimize the training. 
Model 1: Layer 1 hidden nodes - 58, renu activation, Layer 2 hidden nodes - 29, renu activation, sigmoid output layer activation 
Model 2: Layer 1 hidden nodes - 78, renu activation, Layer 2 hidden nodes - 39, renu activation, sigmoid output layer activation 
Model 3: Layer 1 hidden nodes - 78, sigmoid activation, Layer 2 hidden nodes - 39, sigmoid activation, sigmoid output layer activation 

You can models one and two manipulate the number of hidden nodes and model 3 manipulated the activation. None of these variables had a big effect on the results of roughly 74% accuracy and 53% loss. The accuracy seems good and better than the 50-50 success rate but I am concerned about the loss rate of 53%

<img width="528" alt="Screenshot 2023-06-16 161422" src="https://github.com/supersilver1978/venture_funding/assets/126728866/a4c5a73d-6b5d-44d8-b505-b0c68333a983">

## *Contributor*

- Michelle Silver
- supersilver1978@hotmail.com

---

## *License*

This software is licensed under GNU General Public License v3.0. See the [LICENSE](https://github.com/djohnst914/Loan_Qualifier_New_Feature/blob/main/LICENSE) file for details. 

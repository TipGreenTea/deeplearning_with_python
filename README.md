# EI320A(3) 深度學習使用Python,R70802 (deeplearning_with_python)
This repository is a part of the course EI320A(3) 深度學習使用Python @ 
元智大學Yuan Ze University 

------

## Get started guide

#### 1. Download this repository on your local computer and Unzip the folder

#### 2. Download and Install Anaconda 

https://www.anaconda.com/distribution/

#### 3. Change to course folder

```
cd deeplearning_with_python
```

#### 4. Create the course environment

```
conda env create
```

wait for the environment to create.

#### 5. Activate the environment (Mac/Linux/Windows)
```
conda activate dlwp
```
or
```
source activate dlwp
```

Check that your prompt changed to

```
(dlwp) $
```

#### 6. Launch Jupyter Notebook

```
jupyter notebook
```

#### 6. Open your browser to

```
http://localhost:8888
```
#### 7. Run the Check environment Notebook

Run the notebook `0_Check_Environment.ipynb`. If you see the message:

    Here we go!

You are good to go! Enjoy!

#### Troubleshooting installation
If for some reason you don't see `Houston we are go!`, the simplest solution is to delete the environment and start from scratch again.

To remove the environment:

- close the browser and go back to your terminal
- stop jupyter notebook (CTRL-C)
- deactivate the environment (Mac/Linux):

```
conda deactivate
```
or
```
source deactivate dlwp
```

- deactivate the environment (Windows 10):

```
deactivate dlwp
```

- delete the environment:

```
conda remove -y -n dlwp --all
```

- restart from environment creation and make sure that each steps completes till the end.

#### Updating Conda

One thing you can also try is to update your conda executable. This may help if you already had Anaconda installed on your system.

```
conda update conda
```

These instructions have been tested on:

- Mac OSX Sierra 10.14.1
- Ubuntu 18.04
- Windows 10


------

## Course Outline

| Week | Date | Content |
| --- | --- | --- |
| 1| 2/26 | Welcome to the course <br /> Download & Install Anaconda |
| 2 | 3/5 | Crash Course of Python, Numpy, Pandas, and Matplotlib |
| 3 | 3/12 | Get to know about Data & ML:Classification Models <br /> (Logistic Regression, KNN, SVM, Naive Bayes, Decisition Tree, Random Forest) |
| 4 | 3/19 | ML:Regression Models <br /> (Simple/Multiple/Polynomial Linear Regression)  |
| 5 | 3/26 | ML:Clustering /Apriori Models |
| 6 | 4/2 | **holiday** |
| 7 | 4/9 | Introduction to Deep Learning (ANN) |
| 8 | 4/16 | Advanced & Optimization of (ANN) - ANN Labs <br /> Introduction to Convolutional Neural Network (CNN) |
| 9 | 4/23 | Convolutional Neural Network (CNN) - CNN Labs |
| 10 | 4/30 | Introduction to Recurrent Neural Network (RNN) |
| 11 | 5/7 | Recurrent Neural Network (RNN) - RNN Labs <br /> |
| 12 | 5/14 | Wrap Up all ANN, CNN, RNN <br /> **Project Proposal Presentation** |
| 13 | 5/21 | Generative Adversarial Network (GAN) |
| 14 | 5/28 | Deep NLP, Seq2Seq & Attention Neural Network |
| 15 | 6/4 | Reinforcement Learning (RL) |
| 16 | 6/11 |  N/A |
| 17 | 6/18 | **Final Project Presentation** |

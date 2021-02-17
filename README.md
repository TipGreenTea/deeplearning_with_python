# deeplearning_with_python
This repository is a part of the course deep learning with python @ YZE university
------

## Get started guide

#### 1. Download this repository on your local computer and Unzip the folder

#### 2. Download and Install Anaconda ()

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

#### 5. Activate the environment (Mac/Linux)
```
conda activate dlwp
```

#### 5. Activate the environment (Windows)
```
conda activate dlwp
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




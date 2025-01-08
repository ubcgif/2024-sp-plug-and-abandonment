# 2024-sp-plug-and-abandonment
Notebooks for simulating SP effects in a wellbore plug and abandonment experiment

## Contents
There are 4 notebooks in this repository that SP simulations for plug and abandonment examples. There are two different wellbore geometries considered, and the notebooks contain examples of simulations for steady-state and time-varying flow. 

The notebooks rely on SimPEG to perform these simulations. If you are interested in seeing more details about the SimPEG simulations, please take a look at the [SimPEG documentation](https://docs.simpeg.xyz/latest/index.html) and [SimPEG User Tutorials](https://simpeg.xyz/user-tutorials/). 

## Running the notebooks 

To run these notebooks, you will need to have Python installed on your machine. If you do not, please follow the [instructions in the SimPEG documentation](https://docs.simpeg.xyz/latest/content/getting_started/installing.html#prerequisite-installing-python).

If you are unfamiliar with Python and Jupyter, we recommend viewing the [Transform 2022 tutorial on Getting started in Python](https://transform.softwareunderground.org/2022-getting-started-python).

To run the notebooks in this repository, please:
1. Clone or download the repository. From the command line 
   ```
   git clone https://github.com/ubcgif/2024-sp-plug-and-abandonment.git
   ```
  
2. Change into the `2024-sp-plug-and-abandonment` directory 
   ```
   cd 2024-sp-plug-and-abandonment
   ```
  
3. Create the environment 
   ```
   conda env create -f environment.yml
   ```

4. Activate that environment 
   ```
   conda activate 2024-sp-plug-and-abandonment
   ```

5. Run the script, or launch Jupyter using 
   ```
   jupyter lab
   ```

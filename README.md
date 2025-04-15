# TextSyn

# Synthetic Text as Data: On Usefulness and Limitations

This repository contains the code and experimental setup for the research paper  
**"Synthetic Text as Data: On Usefulness and Limitations."**  

---

## Files

- **ExperimentalSetup.ipynb**  
  Sets up the experimental environment.  
  Running this notebook generates scenario-specific datasets under the `data/` folder.  
  This should be run **first** before executing the experiment notebook.

- **Experiment.ipynb**  
  Contains the main experimental code for the paper.  
  Make sure to run `ExperimentalSetup.ipynb` beforehand, as it prepares the required datasets.  
  This notebook reproduces the results described in the paper.

---

## Environment

All dependencies required for running the notebooks are listed in `environment.yml`.  
To recreate the environment, use the following command:

```bash
conda env create -f environment.yml
```

After installation, activate the environment:

```bash
conda activate <environment_name>
```

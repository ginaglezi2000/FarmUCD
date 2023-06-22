### SARS-CoV-2 project
Will need to align sets of viruses against reference virus (such as Wuhan)
+ Initially protein level for only one protein (such as S ~1200 aa)  
Workflow:   
GISAID/NEXTSTRAIN > dataset > sampling > msa > PHMM

### Computer vision
+ Bacteriophages: Capsid detection
+ Need of parallization?

### Image segmentation 
+ Mask RCNN: transfer learning
+ Need of GPU  
Workflow:  
Images > CV for preliminary automated  annotation > Human > MRCNN

### Molecular Dynamics
+ Yasara
+ GROMACS?

## Installation
```conda env create -n simple -f environment.yml```

## Usage
```FarmUCD$ scripts/myscript.py Gina```
# Ephys
working on ephys data analysis rotation proj.

# Data acquisition

Recordings from rats performing PWM task with 32 channel recordings in mPFC.
**fill in more here eventually**

# Analysis

## Pre-processing

### 1. Prepare for Kilosort

**currently working on & adjusting fxs from Emily**
- get data from .mda or .dat --> .bin
- pre-process:
  - break data files into groups of 8 tetrodes
  - remove large artifacts & noise from outside trial window
      - this is performed so these signals don't consume all the templates in Kilosort
- anything else?

### 2. Kilsort

- run pre-procssed .bin files in Kilosort
**fill in setting information**

### 3. Phy Validation

- run kilosort output in phy and determine valid units
**expand**

## Post-processing

### Initial Steps

- bdata integration
- behavior alignment
- PSTHs/spike trig avgs/etc. *think on this more later*
- Running in cluster
- Combine w/ preprocess & run on tigress


#TODO

- determine if pre-kilosort processing will occur in matlab or python
  - see spikegadgets python toolbox
  - see `find_artifacts.m`, `tetrode_32_mdatobin.m`, `rmArtifacts.m`
- determine 'protocol' for phy
- Post-processing




 

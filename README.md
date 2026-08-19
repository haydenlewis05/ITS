# ITS

This project aims to study the detection of Intrinsic Topological Superconductivity using a Josephson Junction under Microwave Irradiation via the Shapiro Effect.

## Authors

Hayden Lewis (MSci Physics)\
Mia Compton (MSci Physics)

## Setup Instructions

### Virtual Enviroment

1. Create a new virtual enviroment from the 'enviroments.yml' file:

```
conda env create -f enviroment.yml
```

2. Activate virtual enviroment:

```
conda activate ITS
```

3. Checking for updates in dependencies:

```
git diff enviroment.yml
```

4. Running updates from 'enviroments.yml' to local venv:

```
conda env update -f enviroment.yml --prune
```

5. If you've added new dependancies and need to update 'enviroments.yml':

```
conda env export --from-history > enviroments.yml
```

### Data

1. The data folder can be found in the OneDrive.

2. Download this and store within your local repo folder.

3. This is included in the '.gitignore' and SHOULD NOT be pushed to the remote.

## Usage Instructions

### ITS

This folder should be used to store all backend scripts that can be exported as packages for use throughout the project in different workflows.

### notebooks

This folder should be used purely for jupyter notebook related activities and should ideally utilise imports from the ITS folder.

### tests

This folder contains both intergration and unit test folders. The former can be utilised to test an entire workflow within the project while the later can be utilised to test specific features or scripts.

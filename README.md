# ITS

This project aims to study the detection of Intrinsic Topological Superconductivity using a Josephson Junction under Microwave Irradiation via the Shapiro Effect.

## Authors

Hayden Lewis (MSci Physics)\
Mia Compton (MSci Physics)

## Setup Instructions

1. Create a new virtual enviroment from the 'enviroments.yml' file:

```
conda env create -f enviroment.yml
```

2. Activate virtual enviroment:

```
conda activate ITS
```

3. Checking for updates in dependancies:

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

## Usage Instructions

TBC
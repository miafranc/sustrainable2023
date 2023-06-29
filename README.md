# SusTrainable Summer School 2023
## Code optimization for sustainable data mining / Code optimization with vectorization in data mining and machine learning

by Zalán Bodó, Lehel Csató, Anikó Kopacz

Although it is possible to use Windows as well, we strongly encourage the participants to use Linux during the lab session.

### Manual installation of Python (>= 3.8.16) and the following packages (with pip):
- numpy
- pandas
- scikit-learn
- nltk

### Using Conda/Miniconda (https://docs.conda.io/en/latest/miniconda.html):
- Install Conda/Miniconda
- Download [environment.yml](https://github.com/miafranc/sustrainable2023/blob/main/environment.yml)
`conda env create -f environment.yml`
- Activate environment:
`conda activate sustrainable2023`

### Using Docker (https://www.docker.com/):
- Install docker
- Pull image (~ 1 GB):
`docker pull zalanbodo/sustrainable2023`
- Run image (by creating a container from it):
`docker run -it -v "[path to local files]:/home" sustrainable2023 /bin/sh`

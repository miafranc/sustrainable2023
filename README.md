# SusTrainable Summer School 2023
## Code optimization for sustainable data mining / Code optimization with vectorization in data mining and machine learning

### Manual installation of Python (>= 3.8.16) and the following packages (with pip):
- numpy
- pandas
- scikit-learn
- nltk

### Using Conda/Miniconda ([https://docs.conda.io/en/latest/miniconda.html]):
- Download [environment.yml](https://github.com/miafranc/sustrainable2023/blob/main/environment.yml)
`conda env create -f environment.yml`
- Modify `prefix` (at the bottom of the file) to point to Miniconda's `envs` subdirectory.
- Activate environment:
`conda activate sustrainable2023`

### Using Docker ([https://hub.docker.com/repository/docker/zalanbodo/sustrainable2023/general]):
- Install docker
- Pull image:
`docker pull zalanbodo/sustrainable2023`
- Run image (by creating a container from it):
`docker run -it -v "[path to local files]:/home" sustrainable2023 /bin/sh`

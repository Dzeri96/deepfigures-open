# deepfigures-open-fixed
================

This is a slightly tweaked version of the original [deepfigures-open repo](https://github.com/allenai/deepfigures-open).
It uses a custom (docker image)[https://hub.docker.com/repository/docker/dzeri96/deepfigures-cpu] to enable running the detection task.
Other functionality was not tested.

## Requirements
- python3
- pip
- pipenv (recommended)
- docker

## Installation
Install the requirements.txt file.
It is recommended to use pipenv as `pipenv install`, because the versions are quite outdated.

Also, make sure you downlaod the above mentioned docker image.

There is no need to download pdffigures2 or the weights since they are pre-built and included in the docker image.

## Usage
For detailed usage, please refer to the original repo.
Just make sure you use the `-s` file to avoid building the docker image because it **will not work**

## Contact

For questions, contact the authors of the paper
[Extracting Scientific Figures with Distantly Supervised Neural Networks][deepfigures-paper].


[deepfigures-paper]: http://arxiv.org/abs/1804.02445
[deepfigures-distant-data]: https://s3-us-west-2.amazonaws.com/ai2-s2-research-public/deepfigures/jcdl-deepfigures-labels.tar.gz
[deepfigures-demo]: http://labs.semanticscholar.org/deepfigures/
[deepfigures-weights]: https://s3-us-west-2.amazonaws.com/ai2-s2-research-public/deepfigures/weights.tar.gz
[pmc-open-access]: https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/
[arxiv-bulk-data]: https://arxiv.org/help/bulk_data_s3

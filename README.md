# Machine learning in high-energy physics
A short introduction to ML in Python with a focus on HEP work.

This tutorial is currently a work in progress; feedback is most welcome.

The data required is available from [CERNBox](https://cernbox.cern.ch/index.php/s/ENW3iemn2qvku5y) and can be aquired via:

```wget https://cernbox.cern.ch/index.php/s/ENW3iemn2qvku5y/download -O csv_data.tgz```

The tutorial can also be run via a Docker image:
1. Install [Docker](https://docs.docker.com/install/)
2. `docker pull lipcomputing/keras-tensorflow`
3. `docker run -d -p 8888:8888 --name=keras lipcomputing/keras-tensorflow`
4. `docker exec keras jupyter notebook list`
5. Take the generated link and load it in a browser, for instance Firefox

The main tutorial is ./classifiers/0_NN_Ensemble_Classifier_New.ipynb
Data is expected to be found in ./Data/

The data used here was been produced by the [AMVA4NewPhysics](https://amva4newphysics.wordpress.com/) Marie Sklodowska-Curie ITN, which is  funded by the Horizon2020 program of the European Commission under grant agreement: 675440.
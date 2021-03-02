# Image Classification on Encrypted Data for Clinical Open-source Viral Infection Diagnosis (ICED-COVID) 

The initial task is to compile and organize existing resources.

The next task will be creating a "proof-of-concept" application that will receive a homomorphically encrypted dataset of medical images, run a machine learning classifier on the data, and return the classifier's encrypted predictions.

## Existing projects for encrypted image classification

- [minkcoregame/privacy-CNN](https://github.com/minkcoregame/privacy-CNN)
  - Project description: This repository provides python code for privacy preserving image classification based on fully homomorphic encryption (FHE).

- [shreyagarge/EncryptedImagePredictorNetwork](https://github.com/shreyagarge/EncryptedImagePredictorNetwork)
  - Project description: Implementation of a Neural Network that predicts encrypted handwritten digits from the MNIST dataset. Encryption and Network Implemented using Homomorphic encryption library SEAL. Model obtained by training on unencrypted images using TensorFlow.
  - License: [GNU General Public License (GPL) v3.0](https://github.com/ibarrond/Pyfhel/blob/master/LICENSE.txt)


## Homomorphic encryption libraries

- [microsoft/SEAL](https://github.com/microsoft/SEAL)
  - Project description: Microsoft SEAL is an easy-to-use and powerful homomorphic encryption library.
  - Languages: C++
  - License: [MIT License](https://github.com/microsoft/SEAL/blob/main/LICENSE)

- [PALISADE](https://palisade-crypto.org/)
  - Project description: PALISADE is an open-source project that provides efficient implementations of lattice cryptography building blocks and leading homomorphic encryption schemes.
  - Languages: C++, with [Python wrapper](https://gitlab.com/palisade/palisade-python-demo) available
  - License: [BSD 2-Clause](https://gitlab.com/palisade/palisade-release/-/blob/master/LICENSE)

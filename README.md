# Image Classification on Encrypted Data for Clinical Open-source Viral Infection Diagnosis (ICED-COVID) 

The initial task is to compile and organize existing resources.

The main goal will be to create a "proof-of-concept" application that will train a machine learning classifier on encrypted images, run the classifier on additional encrypted images, and return the classifier's encrypted predictions.

## Existing projects for encrypted image classification

- [minkcoregame/privacy-CNN](https://github.com/minkcoregame/privacy-CNN)
  - Project description: This repository provides python code for privacy preserving image classification based on fully homomorphic encryption (FHE).

- [shreyagarge/EncryptedImagePredictorNetwork](https://github.com/shreyagarge/EncryptedImagePredictorNetwork)
  - Project description: Implementation of a Neural Network that predicts encrypted handwritten digits from the MNIST dataset. Encryption and Network Implemented using Homomorphic encryption library SEAL. Model obtained by training on unencrypted images using TensorFlow.
  - License: [GNU General Public License (GPL) v3.0](https://github.com/ibarrond/Pyfhel/blob/master/LICENSE.txt)

#### No description or license

- [linaelsadek/ClassificationOverEncryptedImages](https://github.com/linaelsadek/ClassificationOverEncryptedImages)

- [Chaozs/771-Tensorflow-Encrypted-Image-Classification](https://github.com/Chaozs/771-Tensorflow-Encrypted-Image-Classification)



## Homomorphic encryption libraries

- [microsoft/SEAL](https://github.com/microsoft/SEAL)
  - Project description: Microsoft SEAL is an easy-to-use and powerful homomorphic encryption library.
  - Languages: C++
  - License: [MIT License](https://github.com/microsoft/SEAL/blob/main/LICENSE)

- [PALISADE](https://palisade-crypto.org/)
  - Project description: PALISADE is an open-source project that provides efficient implementations of lattice cryptography building blocks and leading homomorphic encryption schemes.
  - Languages: C++, with [Python wrapper](https://gitlab.com/palisade/palisade-python-demo) available
  - License: [BSD 2-Clause](https://gitlab.com/palisade/palisade-release/-/blob/master/LICENSE)

- [OpenMined/PySyft](https://github.com/OpenMined/PySyft)
  - Project description: A library for answering questions using data you cannot see.
  - Languages: Python
  - License: [Apache License 2.0](https://github.com/OpenMined/PySyft/blob/dev/LICENSE)

- [OpenMined/TenSEAL](https://github.com/OpenMined/TenSEAL)
  - Project description: A library for doing homomorphic encryption operations on tensors.
  - Languages: Python, C++
  - License: [Apache License 2.0](https://github.com/OpenMined/TenSEAL/blob/master/LICENSE)

## Research papers

- [A Systematic Comparison of Encrypted Machine Learning Solutions for Image Classification](https://deepai.org/publication/a-systematic-comparison-of-encrypted-machine-learning-solutions-for-image-classification), Veneta Haralampieva, et al., Imperial College London, 2020-11-10

- [On the Security of Homomorphic Encryption on Approximate Numbers](https://eprint.iacr.org/2020/1533), Baiyu Li and Daniele Micciancio, University of California, San Diego, received 2020-12-07, last revised 2021-03-07

## Other resources

- [Homomorphic Encryption Standardization](https://homomorphicencryption.org/)
  - Description: an open consortium of industry, government and academia to standardize homomorphic encryption.

- [Awesome Homomorphic Encryption](https://github.com/jonaschn/awesome-he)
  - Desctiption: A curated list of amazing Homomorphic Encryption libraries, software and resources.

- [CrypTen](https://github.com/facebookresearch/CrypTen)
  - Description: A research tool for secure machine learning in PyTorch. CrypTen currently implements a cryptographic method called secure multiparty computation (MPC), and we expect to add support for homomorphic encryption and secure enclaves in futue releases. 
  - Website: https://crypten.ai/

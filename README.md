# Image Classification on Encrypted Data for Clinical Open-source Viral Infection Diagnosis (ICED-COVID) 

The initial task is to compile and organize existing resources.

The main goal will be to create a "proof-of-concept" application that will train a machine learning classifier on encrypted images, run the classifier on additional encrypted images, and return the classifier's encrypted predictions.

## Existing projects for encrypted image classification

- [minkcoregame/privacy-CNN](https://github.com/minkcoregame/privacy-CNN)
  - Project description: This repository provides python code for privacy preserving image classification based on fully homomorphic encryption (FHE).

- [shreyagarge/EncryptedImagePredictorNetwork](https://github.com/shreyagarge/EncryptedImagePredictorNetwork)
  - Project description: Implementation of a Neural Network that predicts encrypted handwritten digits from the MNIST dataset. Encryption and Network Implemented using Homomorphic encryption library SEAL. Model obtained by training on unencrypted images using TensorFlow.
  - License: [GNU General Public License (GPL) v3.0](https://github.com/ibarrond/Pyfhel/blob/master/LICENSE.txt)

- [fentec-project/neural-network-on-encrypted-data](https://github.com/fentec-project/neural-network-on-encrypted-data)
  - Project description: Demonstrating neural network model applied on encrypted data by using functional encryption.
  - License: [Apache License 2.0](https://github.com/fentec-project/neural-network-on-encrypted-data/blob/master/LICENSE)

<!--
#### No description or license

- [linaelsadek/ClassificationOverEncryptedImages](https://github.com/linaelsadek/ClassificationOverEncryptedImages)

- [Chaozs/771-Tensorflow-Encrypted-Image-Classification](https://github.com/Chaozs/771-Tensorflow-Encrypted-Image-Classification)
-->



## Homomorphic encryption libraries

Library | Description | Language | License
-|-|-|-
[concrete](https://github.com/zama-ai/concrete) | Rust FHE library that implements Zama's variant of TFHE. | Rust | [GNU Affero General Public License (AGPL) v3.0](https://github.com/zama-ai/concrete/blob/master/concrete/LICENSE) (concrete/concrete/LICENSE)
[cuFHE](https://github.com/vernamlab/cuFHE) | CUDA-accelerated Fully Homomorphic Encryption Library. | C++ |  [MIT License](https://github.com/vernamlab/cuFHE/blob/master/LICENSE)
[cuHE](https://github.com/vernamlab/cuHE) | GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs. | C++ |  [MIT License](https://github.com/vernamlab/cuHE/blob/master/LICENSE)
[cuYASHE](https://github.com/cuyashe-library/cuyashe) | Based on leveled fully HE scheme YASHE for GPGPUs. | C++ | [GNU General Public License (GPL) v3.0](https://github.com/cuyashe-library/cuyashe/blob/master/COPYING)
[FHEW](https://github.com/lducas/FHEW) | A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816). | C++ |  [GNU General Public License (GPL) v2.0, or (at your option) any later version](https://github.com/lducas/FHEW/blob/master/LICENSE)
[FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) | A header-only library implementing the Fan-Vercauteren scheme. | C++ | [GNU General Public License (GPL) v3.0](https://github.com/CryptoExperts/FV-NFLlib/blob/master/LICENSE)
<a name="HEAAN">[HEAAN](https://github.com/snucrypto/HEAAN) | Scheme with native support for fixed point approximate arithmetic. | C++ | [Creative Commons Attribution-NonCommercial 3.0 Unported (CC BY-NC 3.0)](https://github.com/snucrypto/HEAAN/blob/master/LICENSE)
[HEAAN-Python](https://github.com/Huelse/HEAAN-Python) | Python binding for the [HEANN](#HEAAN) library. | Python | [MIT License](https://github.com/Huelse/HEAAN-Python/blob/master/LICENSE)
<a name="HElib">[HElib](https://github.com/HomEnc/HElib) | BGV scheme with bootstrapping and the Approximate Number CKKS scheme. | C++ | [Apache License 2.0](https://github.com/homenc/HElib/blob/master/LICENSE.md)
[HEMat](https://github.com/K-miran/HEMat) | C++ implementation of matrix computation (addition, multiplication, and transposition) using [HEANN](#HEAAN). | C++ | [MIT License](https://github.com/K-miran/HEMat/blob/master/LICENSE)
[krypto](https://github.com/kryptnostic/krypto) | C++ implementation of multivariate quadratic FHE. | C++ |
[Λ ○ λ](https://github.com/cpeikert/Lol) | "Lol" Haskell library for ring-based lattice cryptography that supports FHE. | Haskell | [GNU General Public License (GPL) v3.0](https://github.com/cpeikert/Lol/blob/master/lol/LICENSE) (Lol/lol/LICENSE)
<a name="lattigo">[lattigo](https://github.com/ldsec/lattigo) | Go library for lattice-based crypto that implements various schemes. | Go | [Apache License 2.0](https://github.com/ldsec/lattigo/blob/master/LICENSE)
[libScarab](https://github.com/hcrypt-project/libScarab) | C library implementing a FHE scheme using large integers. | C | [Educational or academic use.](https://github.com/hcrypt-project/libScarab#license)
[libshe](https://github.com/bogdan-kulynych/libshe) | Symmetric somewhat HE library based on DGHV scheme. | C++ | [GNU General Public License (GPL) v3.0](https://github.com/bogdan-kulynych/libshe/blob/master/LICENSE)
<a name="SEAL">[Microsoft SEAL](https://github.com/microsoft/SEAL) | C++ FHE library implementing BFV and CKKS schemes.</a> | C++ | [MIT License](https://github.com/microsoft/SEAL/blob/main/LICENSE)
[NFLlib](https://github.com/quarkslab/NFLlib) | NTT-based Fast Lattice library specialized on power-of-two polynomials. | C++ | [MIT License](https://github.com/quarkslab/NFLlib/blob/master/MIT_LICENSE.txt)
[node-seal](https://github.com/morfix-io/node-seal) | JavaScript/WebAssembly port of [Microsoft SEAL](#SEAL). | JavaScript/WebAssembly | [MIT License](https://github.com/morfix-io/node-seal/blob/master/LICENSE)
[NuFHE](https://github.com/nucypher/nufhe) | GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms. | Python | [GNU General Public License (GPL) v3.0](https://github.com/nucypher/nufhe/blob/master/LICENSE.md)
<a name="PALISADE">[PALISADE](https://palisade-crypto.org/software-library) | Efficient implementations of lattice cryptography building blocks and leading homomorphic encryption schemes. | C++, with [Python wrapper](https://gitlab.com/palisade/palisade-python-demo) available | [BSD 2-Clause](https://gitlab.com/palisade/palisade-release/-/blob/master/LICENSE)
[petlib](https://github.com/gdanezis/petlib) | Python library that implements a number of Privacy Enhancing Technologies. | Python |  [BSD 2-Clause](https://github.com/gdanezis/petlib/blob/master/LICENSE.txt)
[Pyfhel](https://github.com/ibarrond/Pyfhel) | A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE). | Python | [GNU General Public License (GPL) v3.0](https://github.com/ibarrond/Pyfhel/blob/master/LICENSE.txt)
[PySyft](https://github.com/OpenMined/PySyft) | Python library for secure and private Deep Learning. | Python | [Apache License 2.0](https://github.com/OpenMined/PySyft/blob/main/packages/syft/LICENSE) (PySyft/packages/syft/LICENSE)
[python-paillier](https://github.com/data61/python-paillier) | Partially HE based on Paillier scheme. | Python | [GNU General Public License (GPL) v3.0](https://github.com/data61/python-paillier/blob/master/LICENSE.txt)
[SEAL-python](https://github.com/Huelse/SEAL-Python/) | Python binding for the [Microsoft SEAL](#SEAL) library. | Python |  [MIT License](https://github.com/Huelse/SEAL-Python/blob/master/LICENSE)
[SparkFHE](https://github.com/SpiRITlab/spark) | Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf). | Apache Spark | [Apache License 2.0](https://github.com/SpiRITlab/spark/blob/master/LICENSE)
[TenSEAL](https://github.com/OpenMined/TenSEAL) | Library for HE operations on tensors, built on [Microsoft SEAL](#SEAL), with a Python API. | Python | [Apache License 2.0](https://github.com/OpenMined/TenSEAL/blob/master/LICENSE)
<a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) | Faster fully HE: Bootstrapping in less than 0.1 seconds.</a> | C++ | [Apache License 2.0](https://github.com/tfhe/tfhe/blob/master/LICENSE)

<!--

- [concrete](https://github.com/zama-ai/concrete) - Rust FHE library that implements Zama's variant of TFHE.
  - License: [GNU Affero General Public License (AGPL) v3.0](https://github.com/zama-ai/concrete/blob/master/concrete/LICENSE) (concrete/concrete/LICENSE)
- [cuFHE](https://github.com/vernamlab/cuFHE) - CUDA-accelerated Fully Homomorphic Encryption Library. (C++)
  - License: [MIT License](https://github.com/vernamlab/cuFHE/blob/master/LICENSE)
- [cuHE](https://github.com/vernamlab/cuHE) - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs. (C++)
  - License: [MIT License](https://github.com/vernamlab/cuHE/blob/master/LICENSE)
- [cuYASHE](https://github.com/cuyashe-library/cuyashe) - Based on leveled fully HE scheme YASHE for GPGPUs. (C++)
  - License: [GNU General Public License (GPL) v3.0](https://github.com/cuyashe-library/cuyashe/blob/master/COPYING)
- [FHEW](https://github.com/lducas/FHEW) - A Fully HE library based on [_FHEW: Bootstrapping Homomorphic Encryption in less than a second_](https://eprint.iacr.org/2014/816). (C++)
  - License: [GNU General Public License (GPL) v2.0, or (at your option) any later version](https://github.com/lducas/FHEW/blob/master/LICENSE)
- [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) - A header-only library implementing the Fan-Vercauteren scheme. (C++)
  - License: [GNU General Public License (GPL) v3.0](https://github.com/CryptoExperts/FV-NFLlib/blob/master/LICENSE)
- <a name="HEAAN">[HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic. (C++)
  - License: [Creative Commons Attribution-NonCommercial 3.0 Unported (CC BY-NC 3.0)](https://github.com/snucrypto/HEAAN/blob/master/LICENSE)
- [HEAAN-Python](https://github.com/Huelse/HEAAN-Python) - Python binding for the [HEANN](#HEAAN) library.
  - License: [MIT License](https://github.com/Huelse/HEAAN-Python/blob/master/LICENSE)
- <a name="HElib">[HElib](https://github.com/HomEnc/HElib) - BGV scheme with bootstrapping and the Approximate Number CKKS scheme. (C++)
  - License: [Apache License 2.0](https://github.com/homenc/HElib/blob/master/LICENSE.md)
- [HEMat](https://github.com/K-miran/HEMat) - C++ implementation of matrix computation (addition, multiplication, and transposition) using [HEANN](#HEAAN).
  - License: [MIT License](https://github.com/K-miran/HEMat/blob/master/LICENSE)
- [krypto](https://github.com/kryptnostic/krypto) - C++ implementation of multivariate quadratic FHE.
- [Λ ○ λ](https://github.com/cpeikert/Lol) - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
  - License: [GNU General Public License (GPL) v3.0](https://github.com/cpeikert/Lol/blob/master/lol/LICENSE) (Lol/lol/LICENSE)
- <a name="lattigo">[lattigo](https://github.com/ldsec/lattigo) - Go library for lattice-based crypto that implements various schemes.
  - License: [Apache License 2.0](https://github.com/ldsec/lattigo/blob/master/LICENSE)
- [libScarab](https://github.com/hcrypt-project/libScarab) - C library implementing a FHE scheme using large integers.
  - License: [Educational or academic use.](https://github.com/hcrypt-project/libScarab#license)
- [libshe](https://github.com/bogdan-kulynych/libshe) - Symmetric somewhat HE library based on DGHV scheme. (C++)
  - License: [GNU General Public License (GPL) v3.0](https://github.com/bogdan-kulynych/libshe/blob/master/LICENSE)
- <a name="SEAL">[Microsoft SEAL](https://github.com/microsoft/SEAL) - C++ FHE library implementing BFV and CKKS schemes.</a>
  - License: [MIT License](https://github.com/microsoft/SEAL/blob/main/LICENSE)
- [NFLlib](https://github.com/quarkslab/NFLlib) - NTT-based Fast Lattice library specialized on power-of-two polynomials. (C++)
  - License: [MIT License](https://github.com/quarkslab/NFLlib/blob/master/MIT_LICENSE.txt)
- [node-seal](https://github.com/morfix-io/node-seal) - JavaScript/WebAssembly port of [Microsoft SEAL](#SEAL).
  - License: [MIT License](https://github.com/morfix-io/node-seal/blob/master/LICENSE)
- [NuFHE](https://github.com/nucypher/nufhe) - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms. (Python)
  - License: [GNU General Public License (GPL) v3.0](https://github.com/nucypher/nufhe/blob/master/LICENSE.md)
- <a name="PALISADE">[PALISADE](https://palisade-crypto.org/software-library) - Efficient implementations of lattice cryptography building blocks and leading homomorphic encryption schemes. (C++, with [Python wrapper](https://gitlab.com/palisade/palisade-python-demo) available)
  - License: [BSD 2-Clause](https://gitlab.com/palisade/palisade-release/-/blob/master/LICENSE)
- [petlib](https://github.com/gdanezis/petlib) - Python library that implements a number of Privacy Enhancing Technologies.
  - License: [BSD 2-Clause](https://github.com/gdanezis/petlib/blob/master/LICENSE.txt)
- [Pyfhel](https://github.com/ibarrond/Pyfhel) - A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE).
  - License: [GNU General Public License (GPL) v3.0](https://github.com/ibarrond/Pyfhel/blob/master/LICENSE.txt)
- [PySyft](https://github.com/OpenMined/PySyft) - Python library for secure and private Deep Learning.
  - License: [Apache License 2.0](https://github.com/OpenMined/PySyft/blob/main/packages/syft/LICENSE) (PySyft/packages/syft/LICENSE)
- [python-paillier](https://github.com/data61/python-paillier) - Partially HE based on Paillier scheme.
  - License: [GNU General Public License (GPL) v3.0](https://github.com/data61/python-paillier/blob/master/LICENSE.txt)
- [SEAL-python](https://github.com/Huelse/SEAL-Python/) - Python binding for the [Microsoft SEAL](#SEAL) library.
  - License: [MIT License](https://github.com/Huelse/SEAL-Python/blob/master/LICENSE)
- [SparkFHE](https://github.com/SpiRITlab/spark) - Apache Spark with an add-on for FHE computations. See [:page_facing_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
  - License: [Apache License 2.0](https://github.com/SpiRITlab/spark/blob/master/LICENSE)
- [TenSEAL](https://github.com/OpenMined/TenSEAL) - Library for HE operations on tensors, built on [Microsoft SEAL](#SEAL), with a Python API.
  - License: [Apache License 2.0](https://github.com/OpenMined/TenSEAL/blob/master/LICENSE)
- <a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) - Faster fully HE: Bootstrapping in less than 0.1 seconds. (C++)</a>
  - License: [Apache License 2.0](https://github.com/tfhe/tfhe/blob/master/LICENSE)

-->

## Research 

### Overview

- [Computing Arbitrary Functions of Encrypted Data](https://cacm.acm.org/magazines/2010/3/76272-computing-arbitrary-functions-of-encrypted-data/fulltext). Craig Gentry. 2010. ([PDF](https://crypto.stanford.edu/craig/easy-fhe.pdf))

### Surveys, reviews, and summaries of research

- [Confidential Machine Learning on Untrusted Platforms: A Survey](https://deepai.org/publication/confidential-machine-learning-on-untrusted-platforms-a-survey). Sagar Sharma, Keke Chen. 2020-12-15.

- [A Systematic Comparison of Encrypted Machine Learning Solutions for Image Classification](https://deepai.org/publication/a-systematic-comparison-of-encrypted-machine-learning-solutions-for-image-classification). Veneta Haralampieva, Daniel Rueckert, Jonathan Passerat-Palmbach. 2020-11-10.


### Additional research papers and studies

- [Efficient CNN Building Blocks for Encrypted Data](https://deepai.org/publication/efficient-cnn-building-blocks-for-encrypted-data). Nayna Jain, Karthik Nandakumar, Nalini Ratha, Sharath Pankanti, Uttam Kumar. 2021-01-30.

- [On the Security of Homomorphic Encryption on Approximate Numbers](https://eprint.iacr.org/2020/1533). Baiyu Li, Daniele Micciancio. Received 2020-12-07, last revised 2021-03-07.

- [CaRENets: Compact and Resource-Efficient CNN for Homomorphic Inference on Encrypted Medical Images](https://deepai.org/publication/carenets-compact-and-resource-efficient-cnn-for-homomorphic-inference-on-encrypted-medical-images). Jin Chao, Ahmad Al Badawi, Balagopal Unnikrishnan, Jie Lin, Chan Fook Mun, James M. Brown, J. Peter Campbell, Michael Chiang, Jayashree Kalpathy-Cramer, Vijay Ramaseshan Chandrasekhar, Pavitra Krishnaswamy, Khin Mi Mi Aung. 2019-01-29.


## Other resources

- [Homomorphic Encryption Standardization](https://homomorphicencryption.org/)
  - Description: an open consortium of industry, government and academia to standardize homomorphic encryption.

- [Awesome Homomorphic Encryption](https://github.com/jonaschn/awesome-he)
  - Desctiption: A curated list of amazing Homomorphic Encryption libraries, software and resources.

- [CrypTen](https://github.com/facebookresearch/CrypTen)
  - Description: A research tool for secure machine learning in PyTorch. CrypTen currently implements a cryptographic method called secure multiparty computation (MPC), and we expect to add support for homomorphic encryption and secure enclaves in futue releases. 
  - Website: https://crypten.ai/

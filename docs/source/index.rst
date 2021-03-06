.. tf-encrypted documentation master file, created by
   sphinx-quickstart on Tue Oct  9 10:51:37 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

TF Encrypted
========================================

TF Encrypted is a Python library built on top of TensorFlow_ for researchers and practitioners to experiment with privacy-preserving machine learning. It provides an interface similar to that of TensorFlow, and aims at making the technology readily available without first becoming an expert in machine learning, cryptography, distributed systems, and high performance computing.

In particular, the library focuses on:

- **Usability**: The API and its underlying design philosophy make it easy to get started, use, and integrate privacy-preserving technology into pre-existing machine learning processes.
- **Extensibility**: The architecture supports and encourages experimentation and benchmarking of new cryptographic protocols and machine learning algorithms.
- **Performance**: Optimizing for tensor-based applications and relying on TensorFlow's backend means runtime performance comparable to that of specialized stand-alone frameworks.
- **Community**: With a primary goal of pushing the technology forward the project encourages collaboration and open source over proprietary and closed solutions.
- **Security**: Cryptographic protocols are evaluated against strong notions of security and [known limitations](#known-limitations) are highlighted.

Checkout the `Getting Started`_ guide to learn how to get up and running with private machine learning.

You can view the project source, contribute, and asks questions on `GitHub`_.

.. _TensorFlow: https://www.tensorflow.org
.. _Getting Started: usage/getting_started.html
.. _GitHub: https://github.com/mortendahl/tf-encrypted


-----------------------
License
-----------------------

This project is licensed under the Apache License, Version 2.0 (see `License`_). Copyright as specified in the `NOTICE`_ contained in the code base.

.. _License: https://github.com/mortendahl/tf-encrypted/blob/master/LICENSE
.. _NOTICE: https://github.com/mortendahl/tf-encrypted/blob/master/NOTICE

.. toctree::
   :maxdepth: 2
   :caption: Getting Started

   usage/installation
   usage/getting_started

.. toctree::
   :maxdepth: 2
   :caption: Guides

   guides/mnist
   guides/logistic_regression

.. toctree::
   :maxdepth: 5
   :caption: API

   api/protocol/index
   api/session
   api/config/config
   api/layers/index

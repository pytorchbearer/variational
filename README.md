[![Python 2.7 | 3.5 | 3.6 | 3.7](https://img.shields.io/badge/python-2.7%20%7C%203.5%20%7C%203.6%20%7C%203.7-brightgreen.svg)](https://www.python.org/) 
[![PyTorch 1.1.0](https://img.shields.io/badge/pytorch-1.1.0-brightgreen.svg)](https://pytorch.org/) 
[![Build Status](https://travis-ci.com/pytorchbearer/variational.svg?branch=master)](https://travis-ci.com/pytorchbearer/variational)
[![Documentation Status](https://readthedocs.org/projects/variational/badge/?version=latest)](https://variational.readthedocs.io/en/latest/?badge=latest)


# \[WIP\] torchbearer.variational
A Variational Auto-Encoder library for PyTorch with torchbearer

## Contents
- [About](#about)
- [Installation](#installation)
- [Goals](#goals)

<a name="about"/>

## About

Torchbearer.variational is a companion package to [torchbearer](https://github.com/ecs-vlc/torchbearer) which is intended to
re-implement state of the art models and practices relating to the world of Variational Auto-Encoders (VAEs). The goal
is to provide everything from useful abstractions to complete re-implementations of papers. This is in order to support
both research and teaching / learning regarding VAEs.

<a name="installation"/>

## Installation

The easiest way to install visual is with pip:

`pip install torchbearer-variational`

Alternatively, build from source with:

`pip install git+https://github.com/pytorchbearer/variational`

<a name="goals"/>

## Goals

Currently, _variational_ only includes abstractions for simple VAEs and some accompaniments, the next steps are as follows:

- Construct some separate part of the docs for the _variational_ content
- Implement a series of standard models with associated notes pages and example usages
- Implement other divergences not in PyTorch such as MMD, Jensen-Shannon, etc.
- Implement and document tools for sampling the latent spaces of models and producing figures
- Implement other dataloaders not in torchvision and add associated docs
[![Build Status](https://travis-ci.org/torch/nn.svg?branch=master)](https://travis-ci.org/torch/nn)
<a name="nn.dok"/>
# Neural Network Package #

This package provides an easy way to build and train simple or complex
neural networks. The documentation is divided into different sections:
 * Modules are the bricks used to build neural networks. Each are themselves neural networks, but can be combined with other networks using containers to create complex neural networks:
   * [Module](doc/module.md#nn.Module) : abstract class inherited by all modules;
   * [Containers](doc/containers.md#nn.Containers) : container classes like [Sequential](doc/containers.md#nn.Sequential), [Parallel](doc/containers.md#nn.Parallel) and [Concat](doc/containers.md#nn.Concat);
   * [Transfer functions](doc/transfer.md#nn.transfer.dok) : non-linear functions like [Tanh](doc/transfer.md#nn.Tanh) and [Sigmoid](doc/transfer.md#nn.Sigmoid);
   * [Simple layers](doc/simple.md#nn.simplelayers.dok) : like [Linear](doc/simple.md#nn.Linear), [Mean](doc/simple.md#nn.Mean), [Max](doc/simple.md#nn.Max) and [Reshape](doc/simple.md#nn.Reshape); and
   * [Convolution layers](doc/convolution.md#nn.convlayers.dok) : [Temporal](doc/convolution.md#nn.TemporalModules),  [Spatial](doc/convolution.md#nn.SpatialModules) and [Volumetric](doc/convolution.md#nn.VolumetricModules) convolutions ; 
 * [Criterions](doc/criterion.md#nn.Criterions) compute a gradient according to a given loss function given an input and a target. Common criterions are :
   * [MSECriterion](doc/criterion.md#nn.MSECriterion) : the Mean Squared Error criterion used for regression; and 
   * [ClassNLLCriterion](doc/criterion.md#nn.ClassNLLCriterion) : the Negative Log Likelihood (cross-entropy) criterion used for classification;
 * Additional documentation :
   * [Overview](doc/overview.md#nn.overview.dok) of the package essentials including modules, containers and training;
   * [Training](doc/training.md#nn.traningneuralnet.dok) : how to a neural network using [StochasticGradient](doc/training.md#nn.StochasticGradient) or with with [your own loop](doc/training.md#nn.DoItYourself) ; and
   * [Testing](doc/testing.md) : how to test your modules.

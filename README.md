# Micrograd

Hi everyone. 
This is a small auto-gradient engine. It implements backpropagation over a dynamically built DAG and small neural networks library on top of it with a Pytorch-like API. This is fully implemented in under 155 lines of code. The DAG only operates over scalar values (As opposed to multi-dimensional tensors), so e.g. we chop up each neuron into all of its individual tiny adds and multiplies. However, this is enough to build up entire deep neural nets doing binary classification.

Full credit to Andrej Karpathy. An absolutely wonderful teacher who helped me get started with neural networks.


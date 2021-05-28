# Transformations between deep neural networks

We propose to test, and when possible establish, 
an equivalence between two different artificial neural networks 
by attempting to construct a data-driven transformation
between them, using manifold-learning techniques.
In particular, we employ diffusion maps with a Mahalanobis-like metric.
If the construction succeeds, the two networks can be thought of as belonging to the same equivalence class.
We first discuss transformation functions between only the {\em outputs} of the two networks;
we then also consider
transformations that take into account outputs (activations)  of a number of internal neurons from each network.
In general, Whitney's theorem dictates the number of measurements from one of the networks 
required to reconstruct each and every feature of the second network.
The construction of the transformation function relies on a consistent, *intrinsic* representation of the 
network input space.

We illustrate our algorithm by matching neural network pairs trained to learn
(a) observations of scalar functions;
(b) observations of two-dimensional vector fields; and 
(c) representations of images of a moving three-dimensional object (a rotating horse).
We also demonstrate reconstruction of a network's input (and output)
from minimal partial observations of intermediate neuron activations.
The construction of equivalences across different network instantiations clearly relates to transfer learning.
It will be valuable in establishing equivalence between
different Machine Learning-based models of the same phenomenon observed through different instruments/research groups.

## License

MIT License

Copyright (c) [2021] [matching-transforming-anns contributors]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

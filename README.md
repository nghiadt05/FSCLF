# FSCLF_Params
This repo reports the trained parameters $\bm{\omega}$ in the following paper: (paper title).
In case of the full-precision format, some of the weights have negative values, which indicates that the back-prop algorithm tries to memorize which bit location has a high chance of being incorrectly decoded. However, to improve generalization, all the negative weights have to be set to 0 in the decoding. On the other hand, the weights under the q(3,5) quantization format is always fixed to be in the interval of [0,+\infty).

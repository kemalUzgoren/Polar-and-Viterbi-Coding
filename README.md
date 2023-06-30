# Polar-and-Viterbi-Coding
Channel encoder performance analysis

This MATLAB code processes message sequences using polar encoders and Viterbi encoders. 
First, the message sequence is separately encoded using the polar encoder and the Viterbi encoder. 
Then, AWGN (Additive White Gaussian Noise) is added to the generated codes to simulate the effects 
of real-world channels. Subsequently, the polar decoder and the Viterbi decoder are used to decode 
these codes and obtain the original message sequences. However, the usage of this code is not limited 
to channel coding methods alone. We also analyze the performance obtained when the message sequence is 
transmitted without applying any channel encoder, using only BPSK modulation. This allows for performance 
comparison among different coding methods. This code serves as a valuable tool for those interested in 
communication systems and channel coding. It not only demonstrates how polar and Viterbi coding algorithms
work but can also be used to evaluate communication performance under real-world conditions. The usage of 
the code is straightforward. By running it in the MATLAB environment, you can use the 'polar_viterbi.m' file.
The code will generate a result report containing error rates and performance metrics.

![polar_viterbi](https://github.com/kemalUzgoren/Polar-and-Viterbi-Coding/assets/66675706/f4444e0f-0cb2-4d5d-a875-89aef9db3547)

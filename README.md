# Linear-Discriminant-Function-for-FHSS-Classification
This repository contains the implementation of the linear discriminant (LD) function for the classification of FHSS Signals by comparing estimated and ideal parameters.

Frequency-hopping spread spectrum (FHSS) spreads the signal over a large bandwidth where the carrier frequencies change quickly according to a pseudorandom
number making signal classification difficult. Furthermore, classification becomes more complex with the presence of additive white Gaussian noise (AWGN)
and interference due to background signals. In this paper, a linear discriminant (LD) method based on the Euclidean distance is proposed for the classification of FHSS
signals in the presence of AWGN and background signal. Probability of correct classification (PCC) of the FHSS signals is performed by the LD method for the
signal-to-noise ratio (SNR) range of −6 to 15 dB. Results show that the proposed method has achieved 90% detection rate at the SNR range of −1.6 to 3.5 dB in the
presence of AWGN only, while its performance is degraded to 0.9 to 12 dB when the background signal is present.

# Codes
Run the main files for each FHSS signal to perform the Monte Carlo Simulation. Note that fastest, fast, medium, slow, and slowest correspond to FHSS_1, FHSS_2, FHSS_3, FHSS_4, and FHSS_5, respectively. Change the background signal power by changing 'strong' to strongest or weak. Here, strongest, strong, and weak refer to Case 4, Case 3, and Case 2, respectively, whereas for Case 1, comment out the background signal line of code.

# Cite this work if you find it useful
Khan, M. T. et al. (2022). FHSS Signals Classification by Linear Discriminant in a Multi-signal Environment." Proceedings of the International e-Conference on Intelligent Systems and Signal Processing, pp. 143-155. DOI: https://doi.org/10.1007/978-981-16-2123-9_11 

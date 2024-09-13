
---

## Project Overview

This project focuses on audio signal processing with the following key objectives:

1. **Echo Generation**: Implementing an echo effect on a given audio signal by introducing a delayed and attenuated version of the original signal. The delay and attenuation are customizable, and the echo decays over time.

2. **Echo Removal**: Utilizing the Normalized Least Mean Square (NLMS) algorithm to remove the echo from a given signal by minimizing the error between the original and echoed signals, aiming to produce a signal close to the original.

3. **Noise Classification**: Classifying different types of background noise (e.g., fan, pump) in an audio signal that contains both music and noise using cross-correlation. This method detects the noise type by analyzing the similarity between signals.

---

# OE-Article-01
Supplementary Data: Improving Sampling Prediction Reliability in Optical System Misalignment Space Based on Cavity Detection

`OpticalSystem.seq`: Optical system file used in the paper.

`Dall_40466.csv`: Full sample set $\mathcal{D}_{\text{all}}$ of 40,466 points, containing 10-dimensional adjustment coordinates, Fringe Zernike terms for each of the 5 fields, X- and Y-direction MTF, and WFE.

`Calvites_Found_500Groups\`: Cavity results found with ACDD algorithm on random 20,000 points deletion from `Dall_40466.csv`. 500 trials.

`PredictedPoints\`: For groups 44# (largest $\mathcal{D}_-$), 78# (fewest $\mathcal{D}_-$), and 460# (medium $\mathcal{D}_-$), each group's three `.csv` files are prediction results from models trained on $\mathcal{D}_{\text{all}}$, $\mathcal{D}_0+$, and $\mathcal{D}_0$, respectively. Each `.csv` file contains 6,000 points, consisting of the unpredicted and predicted results of the model corresponding to the filename on $\mathcal{D}_{\text{all}}$, $\mathcal{D}_+$, and $\mathcal{D}_0$ for 1,000 points each, in the following order:

- Model's unpredicted results for 1,000 points of $\mathcal{D}_{\text{all}}$
- Model's unpredicted results for 1,000 points of $\mathcal{D}_+$
- Model's unpredicted results for 1,000 points of $\mathcal{D}_0$
- Model's predicted results for 1,000 points of $\mathcal{D}_{\text{all}}$
- Model's predicted results for 1,000 points of $\mathcal{D}_+$
- Model's predicted results for 1,000 points of $\mathcal{D}_0$

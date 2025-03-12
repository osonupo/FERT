# FERT
Facial Expression Recognition Test

The folder "FERT 1.0" contains the PsychoPy version of the test (built using PsychoPy 1.83.04, www.psychopy.org). 
Run the file "FER-T.psyexp" using PsychoPy to run the test. It will output a .csv file in the data subfolder. 

To score the test, run the file "FER-T 1.0 Scoring.R" using R (packages BEST and rstan are required for scoring) and open the .csv file when prompted. Computation may take a while (contact me, I may be able to carry it out for you). 

Update: 
- The old scoring method (`FER-T 1.0 Scoring.R`) previously required the **BEST** and **rstan** packages.
  - Old versions of BEST can be retrieved [here](https://cran.r-project.org/src/contrib/Archive/BEST/) 
- The updated scoring approach replaces the BEST library with a **Bayesian 2PL IRT model (`FERT_single_scoring.R`)**.
- A **new mass scoring function (`FERT_mass_scoring.R`)** has been added for batch processing of participant data.

For any questions about the test and the scoring procedure, do not hesitate to contact me at marcello.passarelli@gmail.com

If you use the FERT, please cite Passarelli, M., Masini, M., Bracco, F., Petrosino, M., & Chiorri, C. (2018). Development and validation of the Facial Expression Recognition Test (FERT). Psychological assessment, 30(11), 1479. http://dx.doi.org/10.1037/pas0000595

Data sharing would be welcome!

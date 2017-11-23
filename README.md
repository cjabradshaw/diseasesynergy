# diseasesynergy
Multi-state, dead-recovery model for 18 years of data from Turretfield rabbit population, South Australia 
Data collected by Biosecurity, South Australia, Department of Primary Industries and Regions

Code accompanies paper in review.

Barnett, LK, TAA Prowse, DE Peacock, GJ Mutze, RG Sinclair, J Kovaliski, BD Cooke, CJA Bradshaw. Previous exposure to myxomatosis reduces survival of European rabbits during outbreaks of rabbit haemorrhagic disease for biological control. Journal of Applied Ecology

Code by Louise K. Barnett
November 2017

Before running the script you will need to install program MARK from
http://www.phidot.org/software/mark/downloads/

Mac and Linux users might find this post helpful:
http://www.phidot.org/forum/viewtopic.php?f=21&t=3233&p=10967&hilit=install+RMark#p10967

# Script 1. Rabbit_Multistate_DeadRecovery
This script is for assessing how previous disease exposure/immunity state and recurring outbreaks of myxomatosis and rabbit haemorrhagic disease affect rabbit survival (S) and immunity state transitions (Psi)

# Script 2. Rabbit_Multistate_Plotting_Output
This script is for plotting the output from script 1. Run script 1 and save the output first.

Notes-

Immunity state / previous exposure categories:
N - Immunity to neither virus
M - Immunity to myxoma virus only
R - Immunity to rabbit haemorrhagic disease virus (RHDV) only
B - Immunity to both viruses

Age groups:
Kittens ≤ 600 g (may have residual maternal immunity to RHD)
Adults > 600 g (unlikely to have residual maternal immunity)

Associated data files include:
- TripCovariates.csv
- CaptureHist.csv

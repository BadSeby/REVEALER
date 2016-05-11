# REVEALER
REVEALER (Repeated Evaluation of VariablEs conditionAL Entropy and Redundancy) is an analysis method specifically suited to find groups of genomic alterations that match in a complementary way, a predefined functional activation, dependency of drug response target profile. The method starts by considering, if available, already known genomic alterations (seed) that are the known causes or are known or assumed associated with the target. REVEALER starts by finding the genomic alteration that best matches the target profile conditional to the known seed profile using the conditional mutual information. The newly discovered alteration is then merged with the seed to form a new summary feature, and then the process repeats itself finding additional complementary alterations that explain more and more of the target profile.
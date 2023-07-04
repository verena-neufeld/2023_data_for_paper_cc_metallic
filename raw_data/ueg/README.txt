This folder contains the UEG data, that has not or only slightly been processed.

"raw_results_bald.csv": UEG data with Baldereschi twist, used for main UEG results.
"raw_results_bald_m_1.5_tol_0.04_rs_4.csv": UEG data with Baldereschi twist, where m=M/N is approximately constant. Used in SM figure S1.
"raw_results_gamma.csv": UEG data without twist (Gamma centered), used in table I and SM section E.

Meaning of columns:
"rs": Wigner-Seitz radius r_s in Bohr.
"baldereschi": Has Baldereschi twist been used? If False, then Gamma-centered.
"N": Number of occupied spinorbitals = number of electrons.
"M": Number of spinorbitals.
"E_{method}_corr": Correlation energy (in hartree) for given method.
"E_{method}_s_corr": Same spin part of correlation energy (in hartree) for given method, used in SCS.
"E_{method}_os_corr": Opposite spin part of correlation energy (in hartree) for given method, used in SCS.
Note that "CCSDT_pt" refers to CCSD(T). "CCSDT_ring" and "CCSDT_rt" refer to ring-CCSDT.


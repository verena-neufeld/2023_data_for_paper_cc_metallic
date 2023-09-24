This folder contains the UEG data, that has been extrapolated to the complete basis set limit (CBS) and then to the thermodynamic limit (TDL).

- "{method}_corr_cbs_tdl_bald.csv" contains CBS TDL data for that method.
- "{method}_s_corr_cbs_tdl_bald.csv" contains CBS TDL same spin data for that method.
- "{method}_os_corr_cbs_tdl_bald.csv" contains CBS TDL opposite spin data for that method.

Meaning of columns:
"rs": Wigner-Seitz radius r_s in Bohr.
"baldereschi": Has Baldereschi twist been used? If False, then Gamma-centered. True for files here.
"e_{method}_corr_pe": CBS TDL correlation energy per electron (in hartree) for given method.
"e_{method}_s_corr_pe": CBS TDL same spin part of correlation energy per electron (in hartree) for given method.
"e_{method}_os_corr_pe": CBS TDL opposite spin part of correlation energy per electron (in hartree) for given method.
"E_{method}_corr_pe_err": Estimated error of CBS TDL correlation energy per electron (in hartree) for given method.
"E_{method}_s_corr_pe_err": Estimated error of CBS TDL same spin part of correlation energy per electron (in hartree) for given method.
"E_{method}_os_corr_pe_err": Estimated error of CBS TDL opposite spin part of correlation energy per electron (in hartree) for given method.


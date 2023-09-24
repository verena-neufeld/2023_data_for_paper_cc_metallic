This folder contains the UEG data, that has been extrapolated to the complete basis set limit (CBS).

- "{method}_corr_cbs_{bald,gamma}.csv" contains CBS data for that method.
- "{method}_s_corr_cbs_{bald,gamma}.csv" contains CBS same spin data for that method.
- "{method}_os_corr_cbs_{bald,gamma}.csv" contains CBS opposite spin data for that method.
- "diff_{method}_dcsd_corr_cbs_{bald,gamma}.csv" contains the CBS energy difference between method and DCSD,
i.e. to get the method's CBS energy, add this difference to the CBS DCSD energy at that number of electrons and rs.

Meaning of columns:
"rs": Wigner-Seitz radius r_s in Bohr.
"baldereschi": Has Baldereschi twist been used? If False, then Gamma-centered.
"N": Number of occupied spinorbitals = number of electrons.
"E_{method}_corr_cbs_pe": CBS correlation energy per electron (in hartree) for given method.
"E_{method}_corr_cbs_pe_err": Estimated error of CBS correlation energy per electron (in hartree) for given method.
"E_{method}_s_corr_cbs_pe": CBS same spin part of correlation energy per electron (in hartree) for given method.
"E_{method}_s_corr_cbs_pe_err": Estimated error of CBS same spin part of correlation energy per electron (in hartree) for given method.
"E_{method}_os_corr_cbs_pe": CBS opposite spin part of correlation energy per electron (in hartree) for given method.
"E_{method}_os_corr_cbs_pe_err": Estimated error of CBS opposite spin part of correlation energy per electron (in hartree) for given method.
"diff_E_{method}_DCSD_corr_cbs_pe": Difference between CBS correlation energy per electron (in hartree) for given method and DCSD.
"diff_E_{method}_DCSD_corr_cbs_pe_err": Estimated difference between CBS correlation energy per electron (in hartree) for given method and DCSD.


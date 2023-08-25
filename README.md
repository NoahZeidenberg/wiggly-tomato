# wiggly-tomato
Drug discovery using bioactivity data from ChEMBL.
This has been adapted from the repository "CDD_ML_Part_1_bioactivity_data.ipynb" from @dataprofessor. I made some small improvements:
* Reduced noise via removal of flagged samples
* Data augmentation via addition of samples reported in Ki (rather than just IC50 by applying the conversion factor reported in Kalliokoski *et al.* (DOI.0061007).
***
Future plans for the project include structural analysis using Bio3D and the SMILE IDs reported in part 1 of the code, as well as a docking simulation between the top 3 samples and the target (Abeta). Feel free to send me an email with any questions, comments or concerns at noahzeidenbergATgmail.com

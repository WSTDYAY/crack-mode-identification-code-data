# Crack-mode identification code and data

The uploaded archive `代码和数据.zip` contains the code and data used for the machine-learning part of the manuscript.

## Contents

- `data/`: AE data and processed GMM-labelled datasets.
- `figures/`: exported figures used for the machine-learning analysis, including KDE/GMM plots, stage-wise RA-AF plots, SVM decision-boundary plots, and the Origin project file.
- `Python/`: original Python scripts used for GMM labelling, stage-wise data processing, KDE plotting, LIBSVM-format conversion, and SVM classification.

## Main data files

- `data/specimen9_stage/data9.xlsx`: AE data of specimen 9 with time, RA, and AF parameters.
- `data/specimen9_stage/GMM_Results.xlsx`: GMM-labelled AE events.
- `data/specimen9_stage/GMM_Results1234.xlsx`: stage-wise GMM-labelled dataset. Sheet1-Sheet4 correspond to Stage I-Stage IV.
- `data/libsvm_results/libsvm_results/GMM_Results1234.txt`: LIBSVM-style input file used for SVM classification.
- `data/GMM_Results/KDE_For_Origin.xlsx`: data used for Origin-based KDE plotting.

## Main scripts

- `Python/3-带时间.py`: calculates RA-AF parameters and performs GMM-based crack-mode labelling with time information.
- `Python/jieduan.py`: combines GMM labels with stage-wise data and generates stage-wise RA-AF plots.
- `Python/4.py`: converts labelled Excel data into LIBSVM-style text format.
- `Python/6.py`: performs SVM classification, cross-validation, and exports SVM decision-boundary plots.
- `Python/KDE.py` and `Python/KDE_S_T.py`: generate KDE-related data and plots.

## Notes

The uploaded files are provided to support reproducibility of the machine-learning analysis in the manuscript.

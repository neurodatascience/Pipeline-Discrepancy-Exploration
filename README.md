# Pipeline Discrepancy Measures vs MRIQC Image Quality Metrics on the Prevent-AD dataset.

## What is what?

* **mriqc_output:** This directory contains the output of MRIQC for Prevent-AD subjects.

* **Prevent-AD.json:** This is NeuroCI cache/output file. In this case it contains left hippocampal volumes for Prevent-AD subjects obtained using both FSL 5.0.9 and FreeSurfer 6.0.0.

* **ashs-t1_L_usegray.csv:** This csv contains left hippocampal volumes outputted by the ASHS pipeline for Prevent-AD subjects.

* **exclusion_list.txt:** Contains a list of filenames that we determined through manual QC to be failed segmentations for at least 1 pipeline.

* **hackathon_qc.ipynb:** Contains the analysis scripts and code to generate figures.

* **json_results.zip:** The zip file containing the contents from the mriqc_output directory.

* **volumes_full.json:** Contains the left hippocampal volumes for all 3 pipelines (FSL, ASHS, FreeSurfer) on Prevent-AD subjects.

* **volumes_full_gen.ipynb:** Has the script to generate volumes_full.json given Prevent-AD.json and ashs-t1_L_usegray.csv.

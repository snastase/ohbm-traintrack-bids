# BIDS and BIDS Apps&mdash;OHBM Brainhack 2020

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![OpenNeuro](https://img.shields.io/badge/Data-OpenNeuro-teal)](https://openneuro.org/datasets/ds002345)
[![DataLad](https://img.shields.io/badge/Data-DataLad-orange)](http://datasets.datalad.org/?dir=/labs/hasson/narratives)

### The benefits of BIDS: data standardization and automated processing for neuroimaging research

![Alt text](https://raw.githubusercontent.com/snastase/ohbm-traintrack-bids/master/bids_logo_trim.png?raw=true&s=100 "BIDS Logo")

This repository accompanies a [TrainTrack](https://ohbm.github.io/hackathon2020/traintrack/) presentation titled "The benefits of BIDS: data standardization and automated processing for neuroimaging research" for [OHBM Brainhack 2020](https://ohbm.github.io/hackathon2020/).

This repository contains example HTML outputs from running MRIQC ([Esteban et al., 2017](https://doi.org/10.1371/journal.pone.0184661)) and fMRIPrep ([Esteban et al., 2019](https://doi.org/10.1038/s41592-018-0235-4)) on the "[Narratives](https://openneuro.org/datasets/ds002345)" data collection ([Nastase et al., 2019](https://doi.org/10.18112/openneuro.ds002345.v1.0.1)). HTML outputs can be rendered using https://htmlpreview.github.io/.

### MRIQC
HTML outputs for an example subject: [`sub-001_T1w.html`](https://htmlpreview.github.io/?https://github.com/snastase/ohbm-traintrack-bids/blob/master/mriqc/sub-001_T1w.html) [`sub-001_task-pieman_run-1_bold.html`](https://htmlpreview.github.io/?https://github.com/snastase/ohbm-traintrack-bids/blob/master/mriqc/sub-001_task-pieman_run-1_bold.html)

Group HTML outputs: [`group_T1w.html`](https://htmlpreview.github.io/?https://github.com/snastase/ohbm-traintrack-bids/blob/master/mriqc/group_T1w.html) [`group_bold.html`](https://htmlpreview.github.io/?https://github.com/snastase/ohbm-traintrack-bids/blob/master/mriqc/group_bold.html)

### fMRIPrep
HTML outputs for an example subject: [`sub-001.html`](https://htmlpreview.github.io/?https://github.com/snastase/ohbm-traintrack-bids/blob/master/fmriprep/sub-001.html)

#### References
* Esteban, O., Birman, D., Schaer, M., Koyejo, O. O., Poldrack, R. A., & Gorgolewski, K. J. (2017). MRIQC: Advancing the automatic prediction of image quality in MRI from unseen sites. *PLoS One*, *12*(9), e0184661. https://doi.org/10.1371/journal.pone.0184661

* Esteban, O., Markiewicz, C. J., Blair, R. W., Moodie, C. A., Isik, A. I., Erramuzpe, A., Kent, J. D., Goncalves, M., DuPre, E., Snyder, M., Oya, H., Ghosh, S. S., Wright, J., Durnez, J., Poldrack, R. A., & Gorgolewski, K. J. (2019). fMRIPrep: a robust preprocessing pipeline for functional MRI. *Nature Methods*, *16*, 111-116. https://doi.org/10.1038/s41592-018-0235-4

* Nastase, S. A., Liu, Y.-F., Hillman, H., Zadbood, A., Hasenfratz, L., Keshavarzian, N., Chen, J., Honey, C. J., Yeshurun, Y., Regev, M., Nguyen, M., Chang, C. H. C., Baldassano, C., Lositsky, O., Simony, E., Chow, M. A., Leong, Y. C., Brooks, P. P., Micciche, E., Choe, G., Goldstein, A., Halchenko, Y. O., Norman, K. A., & Hasson, U. Narratives: fMRI data for evaluating models of naturalistic language comprehension. *OpenNeuro*, ds002345. https://doi.org/10.18112/openneuro.ds002345.v1.0.1

# Temporal Prototype Driven Correction (TPDC)

This repository is for our TPDC paper currently under review, entitled "Investigation of various label correction schemes for the self-supervised speaker verification task". The code of our experiments will be available upon acceptance of our paper. We also include below additional ablation studies for our proposed TPDC label correction method.

# Label correction methods: sensitivity to hyperparameters
In Table 5, we run the different label correction methods with different hyperparameters to assess their sensitivity. Results are reported in terms of ACC and NMI and SV performance in terms of EER
(%) on the Vox1-O test set using CAMSAT-based PLs with and without label filtering.
of these different LC methods.
![](/label_correction_methods_hyperparameters.png).

# Label noise filtering threshold influence on label correction and SV
In Table 3, we show the Label correction (LC) performance of the different LC methods in terms of ACC and NMI and SV performance in terms of EER (%)
on the Vox1-O test set using CAMSAT-based PLs with label filtering using different filtering thresholds τ to analyze the scalabilty and sensitivity
of these different LC methods.
![](/label_correction_ablations_filtering_threshold.png)

# Training batch size influence on label correction and SV
In Table 4, we show the label correction (LC) performance of the different LC methods in terms of ACC and NMI and SV performance in terms of EER
(%) on the Vox1-O test set using CAMSAT-based PLs with label filtering using different batch sizes (BS) to analyze scalabilty and sensitivity
of these different LC methods.
![](/label_correction_ablations_batch_sizes.png).


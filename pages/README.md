## About

To support research on TAAR1 (Trace Amine-Associated Receptor 1) and its role in sleep-wake regulation, the Sleep Neurobiology Laboratory at SRI International provides these relevant datasets. This tool facilitates the organization and sharing of physiological recordings collected from adult male C57BL/6J mice under various pharmacological conditions.

## Methods

### Animals

Adult (>9 weeks) male C57BL/6J mice (n = 8), each weighing >23 g at surgery.

### Recording Protocol

- Mice were acclimated for at least 7 days before data collection.
- Wireless transmitters were activated at ZT23 and turned off at ZT24 the following day.
- EEG and EMG recordings were collected continuously for 25 hours and analyzed using Ponemah software.

### Experimental Design

- Mice received treatments at ZT5.5 and again 30 minutes later at ZT6.
- Drug treatments:
  - D1 receptor antagonist SCH23390 (0.25 mg/kg, i.p.)
  - D2 receptor antagonist eticlopride (1 mg/kg, i.p.)
  - Combination of D1 + D2
  - Saline control
- At ZT6, mice received TAAR1 agonist RO5263397 (1 mg/kg, p.o.) or vehicle (10% DMSO).
- A repeated measures design was used, ensuring a 72-hour washout period between treatments.

## Data overview

This dataset includes EEG and EMG recordings, locomotor activity (LMA), and subcutaneous body temperature (Tsc) collected from adult male C57BL/6J mice. The data were recorded following experimental protocols designed to assess the effects of TAAR1 agonists and dopamine receptor antagonists on sleep-wake states.

- [/edf](:files_path:/original/edf): EDF files exported from NeuroscoreTM CNS Software, containing 1 EEG channel, 1 EMG channel, body temperature (Tsc), signal strength, and gross motor activity (LMA). EEG and EMG data were sampled at 500 Hz, while signal strength and Tsc were recorded at 10 Hz, and activity at 1 Hz using Ponemah software (version 5.20; DSI). The DSI F20-EET wireless transmitters allowed EEG power analysis within the 0.5–60 Hz range.
- [/fft](:files_path:/original/fft): CSV files exported by Somnivore (version 1.1.7.0; Somnivore, Ltd. Pty.), containing epoched (10-second epochs) data, including manually scored sleep states and power spectral density (PSD) analysis from fast Fourier transform (FFT) across 985 frequency bins (0–60.059 Hz).

## Access and usage restrictions

The TAAR1 dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
> 
> [Park S, Heu J, Hoener MC, Kilduff TS. Wakefulness Induced by TAAR1 Partial Agonism in Mice Is Mediated Through Dopaminergic Neurotransmission. Int J Mol Sci. 2024 Oct 22;25(21):11351. doi: 10.3390/ijms252111351. PMID: 39518904; PMCID: PMC11547084.](https://pubmed.ncbi.nlm.nih.gov/39518904/)

Users must include the following text in any Acknowledgements:

> The data collection and analysis were supported by NIH R01NS103529 and R01NS136808.  The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*March 2025*

- Make TAAR1 dataset available for data requests

## References

-	TAAR1 GitHub Documentation: https://github.com/nsrr/taar1-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.

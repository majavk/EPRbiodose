# EPRbiodose
Dose reconstruction algorithm using soda-lime glass and ESR spectroscopy in a case of radiological and/or nuclear accidents.


The electron spin resonance (ESR) method is widely used in the field of chemistry, physics,
biology and many interdisciplinary fields, and the application is growing also in the field of
retrospective dosimetry. ESR detection of dosimetric signals originating from radicals induced
under the influence of ionizing radiation allows to determine the dose absorbed by the casualties
following catastrophic, large-scale radiological events. The ESR technique have been applied
to a wide range of radiological studies, including nuclear bomb detonation (e.g., Hiroshima and
Nagasaki), nuclear power plant accidents (e.g., Chernobyl), radioactive pollution (e.g., Mayak
plutonium facility), and in the future could include terrorist events involving the dispersal of
radioactive materials. 

Most commonly the dose in the accidents is assessed by using the peak-to-peak amplitude
from the 1st derivation of the ESR spectra, but in the lower dose range, necessary for the triage of the 
victims of the accidents, the peak-topeak amplitude is not giving the good dose assessment.

In this project the calibration curve to assess the dose from the soda-lime glass samples from the position 
of maximum of ESR spectra (the magnetic field) and it's shift with the dose
was established and the blind dose was assessed based on the calibration curve.

The EPR spectra of irradiated soda-lime samples in the lower dose range is composed of background spectra,
spectra of non-irradiated sample and the radiation induced spectra.

The EPR psectra for the lower doses in the position of maximum is mixture of the 2 contributions,
the radiaton induced and background spectra, and the position of maximum is shifting with the dose.
According to the model, the background component contribution is exponenatially decreasing with the dose
in the EPR signal and the radiation induced component contribution is exponentially increasing.

This algorithm is making calibration curve, the relationship between the position of the maximum of the EPR spectra
and the dose.
This research is published: https://doi.org/10.1093/rpd/ncy290, https://doi.org/10.1080/10420150.2018.1513003.

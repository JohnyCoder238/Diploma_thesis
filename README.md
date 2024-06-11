## Diploma thesis

Collection of prototype scripts and notebooks oriented on simulated diffraction of light on blazed grating and measurement time estimation

difraction.ipynb - first draft of diffraction modelling where the resulted efficiencies where modelled only for one specific wavelegngth

diffraction_data_processing_and_simulation.ipynb:
class DiffractionAnalytical - implements analytical solution to the Fourier transform of phase change on strictly linear blazed grating
class DiffractionNumerical - uses NumPy's FFT to calculate Fourier transform of phase change on any blazed grating (convex, concave and not full fill factor)
class FileProcessor - utility class for processing CSV files produces by the SAX basic script on Agilent spectrometer
class Envelope - object to store the measured diffraction data for various incident angles, wavelengths and diffraction orders for S and P polarisations as well as for transmission and reflection effiiciencies.

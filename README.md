# Progenitor_Process_Analysis_v2.0
Code for annotation of progenitor cell morphology based on Kalebic et al., 2019. 

# Instructions
This paragraph is a description of the modification to the Progenitor Pipeline Analysis as described in Kalebic et., al 2019, and it is intended to be used as an implementation of the Material and Methods section.
The following modifications were performed from the additional pipeline:
-	The macro (ProgenitorProcessesAnalysis_v.2.0) is now updated to be used on new version of Fiji. The current analyses were performed with Fiji v. 10.03.05.

Briefly, the cells were acquired with a step size of 0.3 μm using a point-scanning confocal systems: either a Leica Stellaris 8 with a Plan-Apochromat 40×/1.3 NA oil immersion objective or a Zeiss LSM980 with a Plan-Apochromat 40×/1.4 NA oil immersion objective. Basal progenitors were distinguished as GFP+ Ki67+ cells in the SVZ and cropped within an area of at least 53 μm x 53 μm surrounding the cell. Cell outline was manually tracked following the GFP signal through the Z stack usingTrackEM2 plugin (Fiji v. 10.03.05). The obtained cell mask was applied to the abovementioned pipeline and the results obtained were plotted in Excel along with other cell morphological parameters. A few seconds are required for the macro to process the manually-annotated cell outline. 
For additional details regarding the installation and running of the macro, we refer to the original description provided in Kalebic et al., 2019.

Kalebic, N., Gilardi, C., Stepien, B., Wilsch-Bräuninger, M., Long, K. R., Namba, T., Florio, M., Langen, B., Lombardot, B., Shevchenko, A., Kilimann, M. W., Kawasaki, H., Wimberger, P., & Huttner, W. B. (2019). Neocortical Expansion Due to Increased Proliferation of Basal Progenitors Is Linked to Changes in Their Morphology. Cell Stem Cell, 24(4), 535-550.e9. https://doi.org/10.1016/j.stem.2019.02.017

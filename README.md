# deMix: A GUI-Based Platform for Automated HDX-MS Data Interpretation and Structural Mapping
<p align="center">
<img align="right" 
 src="https://github.com/seungjinna/deMix/assets/102386164/01bfe68e-e402-42d7-a695-8bad4b11c4d8"/> 
</p> 

## Introduction 
Hydrogen/deuterium exchange mass spectrometry (HDX-MS) is a powerful technique for investigating protein conformational changes and dynamics. However, the growing complexity and scale of HDX-MS datasets present significant challenges for efficient analysis and interpretation. Here, we present deMix, an integrated platform that automates HDX-MS data processing and provides intuitive, multi-perspective visualization. deMix supports bimodal distribution analysis for identifying heterogeneous protein states and EX1 kinetics, and includes advanced features such as differential deuteration profiling, uptake kinetics analysis, and 3D structural mapping. By leveraging AlphaFold-predicted structures, deMix enables precise spatial localization of deuterium incorporation. Through interactive visualization of isotopic distributions, kinetic behavior, and structural context, deMix provides a comprehensive framework for HDX-MS data interpretation, enabling deeper insights into protein dynamics and facilitating structure-guided research.</br>

## What deMix  provides:
![demix_figure](https://github.com/user-attachments/assets/6b120b07-3e26-4b51-bae7-9900a13de557)
1. Peptide centric view (Deuterated Distributions)</br>
- Allows users to compare a natural isotope distribution and the corresponding deuterated isotope distribution in one of HDX experiments     across D2O labeling with theoretical, aggregated (over elution time spans), and manually annotated distributions for the chosen peptide.</br>
- Offers a deuteration rate (or deuterium uptake) plot across D2O labeling time for the selected peptide.</br>
2. Protein centric view (Dynamics)</br>
 - Allows users to view the dynamics of the protein.</br>
 - Offers sequence coverage maps for HDX-MS data. Visually represents the HDX rate of each D2O labeling times within the HDX-MS dataset       using colors (= Heat Map).</br>
3. User-friendly environment</br>
  - Includes intuitive and interactive GUI or features.</br>
  - Allows users to focus more on analysis rather than spend time adapting to the software.</br>

## How to start
1. Download the deMix file based on your OS.</br>
- Download the latest release:
👉 [**deMix_v2.1**](https://github.com/seungjinna/deMix/releases/tag/v2.1)
2. Requirement(s) </br>
  - Java Version > 17.05
    To check (type this in the command prompt) = java - version
    Download java here: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
3. To run:</br>
  - **Windows:** </br>
  1. Download Windows version. & Extract the compressed file.</br>
  2. Double Click the bat file. → Run anyway/Run</br>
  - **macOS:** </br>
  1. Download Windows version. & Extract the compressed file.</br>
  2. Right-click the deMix → Open with Terminal → Open. </br>
  - **Linux:** </br>
  1. Download the linux version. & Extract the compressed file.</br>
  2. Double Click the .sh</br>

* For the detailed explanation, refer to the deMix_manual.</br>

## Data Availability
Download [toy data](https://drive.google.com/file/d/1gcwgn6CB0QOcHKqkPelsM9gXEEKnoW_p/view?usp=sharing)

## Reference
[1] Na, S., Lee, JJ., Joo, J.W.J. et al. deMix: Decoding Deuterated Distributions from Heterogeneous Protein States via HDX-MS. Sci Rep 9, 3176 (2019). [https://doi.org/10.1038/s41598-019-39512-8](https://doi.org/10.1038/s41598-019-39512-8)

## Rights and Permissions
deMix © 2026 is licensed under Creative Commons Attribution-ShareAlike 4.0 International.
This license requires that reusers give credit to the creator. It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, even for commercial purposes. If others remix, adapt, or build upon the material, they must license the modified material under identical terms. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/.
  

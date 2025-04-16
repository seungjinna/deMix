# deMix - A Comprehensive Platform for Automated HDX-MS Data Processing and Visualization
<p align="center">
<img align="right" 
 src="https://github.com/seungjinna/deMix/assets/102386164/01bfe68e-e402-42d7-a695-8bad4b11c4d8"/> 
</p> 

## Introduction 
Hydrogen/deuterium exchange mass spectrometry (HDX-MS) is a powerful technique for studying protein conformational changes and dynamics. We previously developed deMix, a fully automated algorithm for analyzing deuterium uptake (Na et al. 2019 [1]). Here, we introduce an enhanced version of 
deMix with a graphical user interface (GUI), designed to facilitate integrated analysis through comprehensive visualization tools. The new features allow users to explore isotope distribution patterns, HDX rate kinetics, and 3D protein structure mapping in an intuitive manner. By leveraging AlphaFold structural predictions, deMix accurately maps deuterium uptake regions, enabling a more comprehensive interpretation of protein conformational dynamics. This integrated visualization approach offers researchers a versatile framework for analyzing HDX-MS data from multiple perspectives, yielding deeper structural insights and enhancing biological interpretation.</br>

## What deMix  provides:
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
  - [Windows](https://drive.google.com/file/d/1G8iZj8AZ4WlXhxaFODl8WwqONs3mzWCg/view?usp=drive_link)
  - [macOS](https://drive.google.com/file/d/1dgQbIlaiQY2bUXyL4M3zBDOVy7jaN345/view?usp=drive_link)
  - [Linux](https://drive.google.com/file/d/1RtyNF2e7qJRkWMHN5ytXPPX8_JIvlnxD/view?usp=drive_link)
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
deMix © 2025 is licensed under Creative Commons Attribution-ShareAlike 4.0 International.
This license requires that reusers give credit to the creator. It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, even for commercial purposes. If others remix, adapt, or build upon the material, they must license the modified material under identical terms. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/.
  

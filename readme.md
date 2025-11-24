
***

## 📚 MLASST Software \[Multi-Layer Anti-Spoofing Simulation Tool\] V1.0 Product Manual

### images referenced in this file are available in the chinese version file [MLASST_Instruction_chinese.pdf](https://github.com/user-attachments/files/23717442/MLASST_Instruction_chinese.pdf)

### Software Introduction


* **Software Name:** Multi-Layer Anti-Spoofing Simulation Tool Software
* **Abbreviation:** MLASST
* **Version Number:** V1.0
* **Software Category:** Application Software (Fill in Application Software/Game Software, etc.)
* **Copyright Holders:** LIU Haiying and MOSES MICHAEL MEITIVYEKI

### Software Features

The features of this software include:
1.  Receiving user input parameters.
2.  Generating data, running simulations, and classifying signals into Clean, Multipath, Jamming, and Spoofing patterns.
3.  Plotting performance charts for different combinations of metrics.
4.  Plotting detector output for analysis.

---

### System Requirements

* **Operating System:** This software is suitable for any operating system running MATLAB (e.g., Windows, MacOS, and Linux), using the **MATLAB APP DESIGNER**.
* **Tested Version:** The final version was tested on a PC running Windows 11 (equipped with an 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz 2.80 GH 64-bit operating system, x64-based processor, 32.0 GB RAM machine) and **MATLAB R2021a**.
* **General Compatibility:** Most computers with lower specifications and older MATLAB versions (that include MATLAB APP DESIGNER) are also expected to run the software.

---

### Installation and Running Methods

#### Installation Method

* Download the software installation package from "\[Download Link Omitted]" (If the link is private, download permission is required, please contact us).
* Follow the prompts to install the software.

#### Running Method

After installation is complete, click the "Icon Pattern" to open the software.

**Method 1: MLASST Executable File**

* **Deployment Prerequisite:** Verify that MATLAB Runtime Version 9.10 (R2021a) is installed. Older versions can also be used.
* **Offline Installation:** If not installed, you can run the MATLAB Runtime installer. Steps 1-9: Run the executable file **MLASST (.exe)** provided in the download to launch the software.
* **For Online Installation:** If the above offline installation file is outdated or incompatible with your system, use the online installation file (requires internet) to download a newer version.
    * Alternatively, to find its location, type `>>mcrinstaller` at the MATLAB prompt.
    * **Note:** You will need administrator privileges to run the MATLAB Runtime installer.
    * Alternatively, download and install the Windows version of the MATLAB Runtime for R2021a from the MathWorks website (Link Omitted). Older versions can also be used.
    * For more information on the MATLAB Runtime and the MATLAB Runtime installer, see **MATLAB Runtime** in the "Distribute Applications" section of the MATLAB Compiler documentation in the MathWorks Documentation Center.
* **Deployed and Packaged Files:** The standalone files to be packaged are:
    * -MLASST.exe
    * -MCRInstaller.exe
    * **Note:** If the end-user cannot download the MATLAB Runtime as instructed in the previous section, include it by clicking the **"Runtime included in package"** link in the Deployment Tool when building the component.
    * To find definitions regarding deployment terminology, go to the MathWorks website (Link Omitted) and select MATLAB Compiler > Getting Started > About Application Deployment > Deployment Product Terms in the MathWorks Documentation Center.

**Method 2: Operating System With MATLAB Installed**

* If MATLAB is already installed on your system (verify that **MATLAB Runtime Version 9.10** is installed):
    * Open the MLASST (English or Chinese version) file **(.mlapp)** provided in the download to launch the regular interface.
    * Click the **"Run" button** indicated by the arrow.
    * **Important:** Ensure all downloaded files and folders (including functions and parameters) have not been deleted or removed from the path.
    * Before use, ensure the **"classes"** and **"functions" folders** are added to your active MATLAB path.

---

### Software Functions

The functions of this software include:

* **Change/Select Language**.
* Button for switching between output graphic modes **(3-dimensional (3D) or 2-dimensional (2D))**.
* Toggle between result types, i.e., **Probability of Missed Detection (PMD)** or **ALARMS** raised.
* Window for selecting the metric combination for simulation.
* Area for changing user input simulation parameters.
* Window for displaying graphical results based on selected parameters and output preferences.
* Button to decide whether to display multiple results on the same display window or to restart for each simulation.
* **Dataset Generation and Implementation**
    * Button for generating simulation data.
    * After simulation data generation, it will be saved as **`MLASST_DATASET`** in the main folder.
    * The dataset can be opened using MATLAB to extract information.

#### Simulation Results and Charts

* Button to start simulation based on selected parameters and output preferences.
* 3D result example
* 2D result example
* The output of the software tool can be displayed in 2D and 3D graphs, showing the average PMD during ascent or alarms under different Spoofer Power Advantages. For example, the figure below shows the 3D plane for the single P and D metrics and the combined metrics of Gate AND, OR, Primary Set, Secondary Set, and MLASC. Any point selected on the plane will provide important detection information about that point in that specific metric plane. These can be isolated and analyzed individually, a process that can be easily done from the software tool by selecting specific metric combinations.
* For example, for the OR gate in the figure below, considering a Spoofing Power Advantage of 10dB, the minimum alarm end has 707,545 alarms, and its PMD is approximately 0.2919. Different points can be extracted from the 3D surface and 2D lines for further analysis. Different combination techniques can also be compared and analyzed. Users can be creative and adjust as many variables for as many metric combinations as possible for analysis and to check the effectiveness of different GNSS anti-spoofing metric combination techniques.
* The following are random examples of results that users can obtain and use from the software based on selected parameters and output preferences. (The user should possess the knowledge required in that specific field for further analysis of the results).

***


***

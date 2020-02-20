## RGA-2019
Notebooks used for preliminary evaluation of RGA scans performed in the 2019 fall run.

#### Data:
- RGAdata_2019: 
  this folder contains csv files exported from the software.
  Each data set consists of five scans.
  The folders are saved in names such as "rga1_Nov_15_2019_05-38-27_PM"
  In it, the files are saved with names such as "Nov_15_2019__05-39-50_PM.txt"

- RGAdata:
  A direct copy from the desktop PC used for the RGA scans.Constains also unnecessary data from early 2019. Sorted them in the folder 'RGAdata_2019'
  
- RGAdata_2019/gaslib/gaslib.dat:
  Library of fragmentation ratio from the SRS which was found in the installation directory of the software 
  
- NIST:
  A few files exported from the online NIST molecular library of fragmentation compound. There are saved in a particular format with the file extension of "jdx".
  
#### Notebook:
- RGA_preliminary-1.ipynb:
  - Cacluate avergae of 4 scans from each data set (reason of skipping the first one is that, often it was observed the first scan has some fluctutation (due to somethings attached on the filament surface?))
  - Evalute the fragmentation mass spectrum, search peak using a scipy library 
  - Plot evolution of the peak heights of the fragmentation mass spectrum as function of time
- SRS_data.ipynb: 
  Notebook created to extract data as a pandas table from the SRS files 
- NIST data.ipynb:
  Notebook created to extract data as a pandas table from the NIST files 

  



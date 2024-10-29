This folder contains three sub-folders:

  Set1CleanedFiles
  Set2CleanedFiles 
  Set3CleanedFiles

These three folders (Set1CleanedFiles, Set2CleanedFiles and Set3CleanedFiles)
contain data on overlapping sets of chemicals. They are all data for the case
of 50g of coffee in a glass jar of volume 3.466 litres.

In each of these folders you will find the following files:

  master_list_chems.txt
  names_list_5.txt
  names_list_20.txt
  names_list_35.txt
  names_list_50.txt
  names_list.txt
  Tdata_5_clean.csv
  Tdata_5_clean.dat
  Tdata_20_clean.csv
  Tdata_20_clean.dat
  Tdata_35_clean.csv
  Tdata_35_clean.dat
  Tdata_50_clean.csv
  Tdata_50_clean.dat

The first file ("master_list_chems.txt") is a master list of chemical names
that are present for at least one temperature. 

The next four ("names_list_5.txt", "names_list_20.txt", "names_list_35.txt"
and "names_list_50.txt") are the names that appear in the data sets for each 
of the four temperatures studied (5C, 20C, 35C and 50C, respectively).

The file "names_list.txt" contains an index number for each chemical in
the master chemcials list, followed by "YES" or "NO" indicating whether
there are data for each of the temperatures (5C, 20C, 35C and 50C, 
respectively), and finally the name of the chemcical, including a suffix
("_1", _2" or "_3") showing the replicate number of the measurement
(see below).

The raw data sets are recorded in two formats: a comma-seperated file 
(".csv") and a space-separated text file (".dat"), which otherwise contain 
the same data in the same format.

Each comma-separated file (for example "Tdata_5_clean.csv", which contains
data taken at 5 degrees Celsius) has a number of columns:

  The first column is just integers indicating the row number, and has no
  further significance.

  The second column is the measurement time in seconds, after the start
  of the experiment..

  Subsequent columns are the head-space concentration of different volatile
  organic compounds, measured in parts per billion, using PTR-MS-ToF.
  Chemical names contain  no commas or spaces, and each has a suffix indicating
  replicate measurements. For example, "Phenol_1", "Phenol_2" and "Phenol_3"
  represent the concentration in the headspace versus time for Phenol,
  for three different runs of the experiment.


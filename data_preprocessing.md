---
title: "Data Preprocessing"
parent: "Data"
layout: default
nav_order: 2
---

# Data Preprocessing

Our data was extracted using 12 different functions in python to extract 14 parameters (3 parameters were extracted using one function) from each waveform. All of these functions were added to master file and were used to extract 14 parameters from each waveform for each file in our testing, training, and NPML data. The way it works is that each function takes in a waveform and extracts the information needed to calculate or create its parameter. This process is combined in our master file and allows us to run each function together for a waveform. The end result is a file with 1 row per waveform and 14 columns that are the parameters that were extracted.

# Ozone_CloudTransmission
Total ozone and Cloud transmittance at local noon (interval of 60 minutes centered around local noon), retrieved from GUV-instruments operating at the UV-network locations, and corresponding daily meain total ozone amount from TOMS/OMI overpass data.
The method for retrieving total ozone from GUV-instruments is described in Dahlback, A., Appl. Opt. Vol. 35, No. 33, 1996.

Calibrations: Ozone data has been corrected for solar zenith angle (SZA) and cloud transmittance, based on a regression against long term series of OMI overpass data. Hence, the ozone data reflects the absolute calibration scale of the OMI instrument.
A validation of agreement between GUV ozone and satellite ozone at different UV-stations is provided in the file Daily_GUV_O3_versus_TOMS_and_OMI_data.svg

Files are organized with the following columns:

Year

Daynumber

SZA: The solar zenith angle at nooon

GUV_Ozone: Total ozone based on GUV-instrument

GUV_CLT: Cloud transmittance at noon

Ozone TOMS/OMI: Total ozone overpass data from TOMS and OMI

GUV-Serialnumber: The serial number of the GUV-541/511 instrument operating at the location

Missing data is indicated with NAN.

Data is provided by Bjørn Johnsen at the Norwegian Radiation and Nuclear Safety Authority (https://DSA.no)

Email: Bjorn.Johnsen@DSA.no

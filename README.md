# Develop-the-Oracle-of-DSCOVR
This project is an extension of the 2023 NASA Hackathon competition theme.

Despite exceeding its expected lifespan, DSCOVR continues to operate. We'll improve Earth's geomagnetic storm predictions by optimizing data with raw data. We'll employ the three-dimensional proton distribution function and magnetic field data (50 vectors per second). Each value denotes the solar wind's flux and flow strength at different energy levels or speeds. These data will undergo AI training, allowing AI to cross-reference them with NOAA historical data for accuracy checks. Ultimately, this AI system will monitor solar wind activity, providing rapid alerts for solar events.

The current project provides only preliminary architectural ideas on how to use DSCOVR data to predict magnetic storms.

We anticipate using DSCOVR's raw data, which includes the magnetic field vector and measurement spectrum from the Faraday cup plasma detector. After passing through an artificial neural network (ANN) model for evaluation, we will obtain a predicted Planetary K-index (Kp). This Kp will then be used to determine whether a magnetic storm is likely to occur.

##**Concept**
![Screenshot 2023-10-08 205639](https://github.com/marumaruchiii/Develop-the-Oracle-of-DSCOVR/assets/89464581/1e9ae7fa-ec24-47fa-8528-6ae064cca05d)


##**SPACE AGENCY DATA:**
[DSCOVR PlasMAG Data](https://www.spaceappschallenge.org/develop-the-oracle-of-dscovr-experimental-data-repository/)
[NOAA REAL TIME SOLAR WIND](https://www.swpc.noaa.gov/products/real-time-solar-wind#)
[NOAA PLASMA Measurements](https://nesdis-prod.s3.amazonaws.com/migrated/dscovr_plasmag_instrument_info_sheet.pdf?_ga=2.101728385.1069921316.1696687224-453793390.1696600630)
[Disturbance Storm Time Index](https://www.ngdc.noaa.gov/stp/geomag/dst.html)
[Kp-Index - Maine.gov](https://www.maine.gov/mema/maine-prepares/preparedness-library/geomagnetic-storms)

##**REFERENCES**:
Faraday Cup Detectors- Prepared by H. H, HILTON and J. R STEVENS Space Physics Laboraiory
Train GRU with PyTorch
Install CUDA
Bokeh








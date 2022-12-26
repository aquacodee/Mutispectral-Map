# DJI Terra Aerial Triangulation Quality Report

---
## Image Information Overview

| Item                    | Value           |
| :---: | :---: |
| # Input Images          |               99|
| # Image With Position   |               99|
| # Calibrated Images     |               99|
| Use Image Position | True|
| Georeferencing RMSE |   0.018 m|
| SFM Time          |        0.567 min|


## RTK Status

| Status  | Number of Images |
| :---: | :---: |
| FIX     |               99|
| FLOAT   |                0|
| SINGLE  |                0|
| NONE    |                0|



## Camera Calibration Information

Camera Model FC6360 

Camera SN 551778b02d260171952b87454bf1ac22 

| Item     | Focal   | Cx      | Cy      | K1  | K2  | K3  | P1  | P2  |
| :---:      | :---:     | :---:     | :---:     | :---: | :---: | :---: | :---: | :---: |
| Initial  | 1953.74| 804.06| 638.18| -0.41080500| 0.33538700| -0.30331400| 0.00141410| 0.00141410|
| Optimized| 1953.68| 802.69| 643.59| -0.41623646| 0.33836499| -0.29309630| 0.00083528| 0.00024773|


Coefficients and correlation matrix 

|      | Error | F     | Cx    | Cy    | K1    | K2    | K3    | P1    | P2    |
|:---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| F  | 0.24868719| 1.00000000| -0.01894461| -0.04925460| -0.18575850| 0.04139373| -0.02527804| 0.13381863| 0.04931920|
| Cx  | 0.14790751| -0.01894461| 1.00000000| 0.03340165| 0.01963725| -0.01242970| 0.00798026| -0.02175351| -0.40246793|
| Cy  | 0.14270978| -0.04925460| 0.03340165| 1.00000000| 0.00352292| 0.00370227| -0.00331667| -0.38889393| -0.00430221|
| K1  | 0.00056900| -0.18575850| 0.01963725| 0.00352292| 1.00000000| -0.95859276| 0.90296915| -0.02495214| -0.01449425|
| K2  | 0.00413367| 0.04139373| -0.01242970| 0.00370227| -0.95859276| 1.00000000| -0.98347334| 0.00130683| -0.01284529|
| K3  | 0.00874016| -0.02527804| 0.00798026| -0.00331667| 0.90296915| -0.98347334| 1.00000000| 0.00324581| 0.01773406|
| P1  | 0.00001006| 0.13381863| -0.02175351| -0.38889393| -0.02495214| 0.00130683| 0.00324581| 1.00000000| -0.01239852|
| P2  | 0.00001061| 0.04931920| -0.40246793| -0.00430221| -0.01449425| -0.01284529| 0.01773406| -0.01239852| 1.00000000|


## Hardware Information

- CPU: Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz
- GPU Number: 1
- GPU0: GeForce GTX 1050 Ti
- RAM: 16252 M
# DJI Terra 2D Quality Report


---
## Process Parameters

| Process Parameters    | Value |
| :---: | :---: |
| Mapping Scene        | Multi-Spectrum    |
| Resolution         | High    |
| Coordinate Correct| No|
| Reflectance Calibration| No |
## TDOM Preview
![TDOM Preview](./dom_screennail.png =1500x1333)

## Map Information Overview

| Item                   | Value           |
| :---: | :---: |
| TDOM GSD               |        0.033 m|
| Coverage Area          | 0.011940 sq km|
| Average Flight Altitude|       64.540 m|
## Performance Overview

| Pipeline              | time cost (min) |
| :---:                 | :---:           |
| Densification         |        0.283|
| TDOM Generate         |        1.567|
## DSM Preview
![DSM Preview](./dsm_screennail.png =1500x1333)
## Scene Overlap Analyze

![Overlap](./overlap_render.png =1500x1333)
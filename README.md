# Design and Performance analysis of Floating solar plant.

## 📚 Table of Contents
1. [Project Overview](#Project-overview)
2. [Proposed Site](#Proposed-site)
3. [Design Methodology](#Design-methodology)
4. [Different variants](#Different-variants)
5. [Environmental Impact](#environmental-impact)
7. [Data & Files](#data--files)

## Project-overview
With the rising demand for clean energy and increasing pressure on land resources, Floating Solar Photovoltaic (FSPV) systems have emerged as a promising alternative to conventional land-based solar installations. India, with its vast network of reservoirs, lakes, and water bodies, has witnessed a surge in FSPV adoption, driven by government initiatives and the need to optimize space utilization in densely populated regions.

This project explores the design and analysis of a 20/22.5 MWp floating solar plant proposed for deployment on Indrapuri barrage in Rohtas, Bihar, India. Unlike traditional ground-mounted systems, FSPV installations offer distinct advantages: they eliminate land acquisition challenges, reduce evaporation losses from water surfaces, and benefit from enhanced energy yield due to reduced ambient temperatures and minimal shading.

The study outlines multiple FSPV variants based on their design layouts and orientations tailored to the proposed site conditions. It evaluates the electrical performance,  and environmental impact of the floating system. The design methodology incorporates site-specific constraints, platform stability, and optimal tilt angles to ensure reliable and efficient energy generation.
<div align="center">
  <table>
  <tr>
    <td><img src="images/indrapuri_barrage.png" height="300"/></td>
    <td><img src="images/google_earth_image.png" height="300"/></td>
  </tr>
  <tr>
    <td align="center"><em>Figure 1: Indrapuri Barrage, Rohtas, Bihar</em></td>
    <td align="center"><em>Figure 2: Google Earth View of the Site</em></td>
  </tr>
  </table>
</div>  

## Proposed-site

The site chosen for the analysis is near the Indrapuri barrage, Rohtas, Bihar, India. It is located over the Sone river.The proposed location is analysed for different variants, its plant capacity and future scalability, and the electrical & performance feasibility for the plant. The geographical location of the project is as follows:  
lattitude of the proposed location- 24.83°  
longitude of the proposed location- 84.13°  
Avg. altitude of the proposed location- 105m

Also, the key hydrological data for the proposed barrage site, including average water depth, seasonal river height variations, and peak flood levels is shown in the following figure. These parameters are essential for designing a stable and resilient floating solar platform.

<p align="center">
  <img src="images/Sone_barrage_specs.png" alt="Sone Barrage Specifications" height="300"/>
</p>
<p align="center"><em>Figure 3: Sone barrage specifications.</em></p>

## Design-methodology 

The floating solar plant design was developed based on site-specific hydrological data, seasonal water level variations, platform stability requirements, and optimal energy yield considerations. The methodology involved selecting suitable PV modules and inverters, and evaluating multiple variants based on their design layouts and orientations.

For our project, the design for the different plant layouts and the shadow analysis is done using the 3D modelling software "Sketchup" and the performance analysis for its electric and performance feasibility is done using Pvsyst 8.0.15. The PVsyst software uses the meteorological data provided below by meteonorm 8.2 for the site specific analysis and to produce tthe performance report.

<div align="center">
  <table>
  <tr>
    <td><img src="images/meteo_data.png" height="300"/></td>
    <td><img src="images/sun_path.png" height="300"/></td>
  </tr>
  <tr>
    <td align="center"><em>Figure 4: Meteorological data of the site </em></td>
    <td align="center"><em>Figure 2: Sun path of the Site</em></td>
  </tr>    
  </table>
</div> 

The different variants of the floating solar plants are realised based on their design layout (with 1.1 MW array block and 2.5 MW array block) and their different orientations. The array block layout is made using "Sketchup" with the consideration of shadows according to the site location.

<div align="center">
  <table>
  <tr>
    <td><img src="images/1.1mw.png" height="300"/></td>
    <td><img src="images/2.5mw_array.png" height="300"/></td>
  </tr>
  <tr>
    <td align="center"><em>Figure 4: 1.1 MW array block </em></td>
    <td align="center"><em>Figure 2: 2.5 MW array block </em></td>
  </tr>    
  </table>
</div> 

## Different-variants
For the project, we have chosen five different variants of FSPV each with some different array layouts, orientations and power capacity output. Let's uncover it one by one:

## 🔧 FSPV Variant 1 Specifications

### 📦 Module Specifications

| Parameter                  | Value                                  |
|---------------------------|----------------------------------------|
| Module                    | Longi 550 Wp, Mono-Si, PERC, Half-cut  |
| Maximum Power Voltage (Vmp) | 41.29 V                              |
| Maximum Power Current (Imp) | 13.32 A                              |
| Open Circuit Voltage (Voc)  | 49.52 V                              |
| Short Circuit Current (Isc) | 14.09 A                              |
| Module Efficiency         | 21.3%                                  |
| Temp. Coefficient of Pmax | -0.350%/°C                             |

### ⚙️ Inverter Specifications

| Parameter                  | Value                  |
|---------------------------|------------------------|
| Inverter                  | Sungrow SG250HX-HV20   |
| AC Output Nominal Power   | 2500 kVA               |
| AC Output Voltage         | 800 V                  |
| Max. DC Input Voltage     | 1500 V                 |
| MPPT Voltage Range        | 800 – 1300 V           |
| Max. Input Current        | 800 A                  |
| Number of MPPTs           | 12                     |
| Efficiency (EU/CEC)       | 98.6%                  |
| Peak Efficiency           | 99%                    |

### 🧭 System Layout

| Parameter       | Value                          |
|----------------|--------------------------------|
| System Layout   | 2.5 MW array at 3%             |
| Array Layout    | 148 Strings in series (2.553 MWp) |
| Panel Ratio     | 1.02                           |
| Orientation     | Fixed Tilt: 5° / Azimuth: 132.5° |



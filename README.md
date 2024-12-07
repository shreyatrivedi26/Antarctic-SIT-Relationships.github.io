<h1 align="center">Antarctic Sea-ice Thickness: Spatio-Temporal Variability and its Relationship with Large-Scale Southern Hemispheric Atmospheric Circulations</h1>
<h2 align="center">Shreya Trivedi and Marilyn Raphael</h2>
<h3 align="center">University of California, Los Angeles (UCLA)</h3>

## Introduction:
1. Sea ice Thickness (SIT) has received limited attention  despite its importance in indicating absolute sea ice changes in the Southern Ocean.
2. Existing studies understanding sea-ice relationships between atmospheric components and Antarctic sea-ice have only focused on the surface parameters such sea ice concentration (SIC), area or extent. 

<br><br>

## Motivation of the Study:  
Results from my previous studies highlighted covariability between SIT and SIC:

![Motivation of study](https://github.com/user-attachments/assets/b99f8128-00ae-466c-9dc2-7755264aacae)

*Figure 1: a) Scatter plots between the annual means of SIT (y-axis) and SIA (x-axis) for CMIP6 models, Reanalyses and Observations for the period (2002-2014) for SIT maxima observed in February and minima observed in September. Each small dot represents a model, larger dots represent observations (Envisat-CryoSat-2 and passive microwave data at NSIDC for SIT and SIA, respectively) while triangles represent reanalyses (GIOMAS and GECCO3). Scale: million km2 (Trivedi et al., 2024; Under Review) b) Monthly averaged anomalies in SIT (shaded), SIA (contours) and 10-m winds (vectors) in CESM2 over preindustrial runs (Aug-Oct for 1200 years). Spatial variabilities in SIT are seen throughout the icepack unlike in SIA which is primarily noticed at the ice edge. “Thickness dipoles” are visible along the coast of Amundsen-Ross Seas (magnified)  i.e., negative anomalies even in regions of cold southerly winds (Trivedi et al., In prep)*

<br><br>

## Objectives/Research Questions:
1. Identifying reasons for covariances between SIT and SIC:<br>
    How do spatial and temporal SIT patterns look around the Antarctic?<br>
    How are they different from SIC patterns?<br><br>
    
2. Understanding the significance of atmospheric drivers on sea-ice: <br>
   How are SIT and atmospheric mode in the southern hemisphere related? <br>
   What are the primary dictating factor for SIT distribution in each region? <br>
   Does SIC respond differently to them?<br><br>

<div style="display: flex; justify-content: space-between;">
   <img src="https://github.com/user-attachments/assets/852f1376-ccaf-4daf-a652-c3e125572e51" alt="image" style="width: 45%;"/>
   <img src="https://github.com/user-attachments/assets/fca7e13a-4e5e-4295-98c3-ebc2e5ef0c54" alt="Climate_Indices" style="width: 60%;"/>
</div>

*Figure 2: a) Dataset and Methodology; b) Time series for the five selected atmospheric circulation indices in the Southern Hemisphere*

<br><br>

## Preliminary Results: 

I. **Contrasting SIT and SIC Variability:** SIT shows distinct opposing anomalies between the Weddell Sea and East Antarctic vs. the Amundsen-Ross regions, a pattern absent in SIC (except in EOF2). Temporally, SIT’s PC1 steeply rises post-2000, unlike SIC.

**EOF1:**
**SIT:** Opposing spatial anomaly pattens  in Weddell-Bellingshausen and Ross-Amundsen.PC1 shows a steady positive increase from 1979-2000s and strengthens 2000 onwards.Maybe linked to broader climate phenomenon such as SAM or long-term atmospheric changes.

<div style="display: flex; justify-content: space-between;">
   <img src="https://github.com/user-attachments/assets/29394bf3-7c83-4ce7-a257-f2cf84a00242" alt="EOF_SIT_ADV" style="width: 45%;"/>
   <img src="https://github.com/user-attachments/assets/9e19983d-eb77-41d5-a849-e9c1364de387" alt="PC_SIT_ADV" style="width: 45%;"/>
</div>

**SIC:** Alternating Zonal patterns around the Antarctic.PC1 shows strong interannual variability i.e. higher magnitudes and amplitudes (1990 onwards).Thermodynamic reasons, with greater melting at the ice edge. 

<div style="display: flex; justify-content: space-between;">
   <img src="https://github.com/user-attachments/assets/a5f1d73f-19fc-4091-be1f-a9644f496b69" alt="EOF_SIC_ADV" style="width: 45%;"/>
   <img src="https://github.com/user-attachments/assets/ff830789-7c66-4ced-8aaa-5adc6c3e1bc2" alt="PC_SIC_ADV" style="width: 45%;"/>
</div>


**EOF2 and 3:**
Similar opposing anomaly patterns in both the parameters. For SIT, changes are throughout the ice-pack while for SIC, they are mostly concentrated at the ice edge.
More oscillatory nature with strong interannual variability.
May be associated with more localized or shorter-term variability (such as ENSO, ASL, ZW3).

<br><br>

II. **Key Atmospheric Influences:** During the Advance season, ZW3, SOI, and ASL significantly drive SIT variability. Regression residuals increase notably when these indices are excluded, highlighting their importance.

<div style="display: flex; justify-content: space-between; align-items: flex-start;">
    <!-- Left side: First image -->
    <div style="flex: 1; margin-right: 10px;">
        <img src="https://github.com/user-attachments/assets/1cda1663-6192-447c-9f63-ea12409cd632" alt="CorrelationMatrix-CI" style="width: 70%;"/>
    </div>
    
    <!-- Right side: Second and Third images stacked -->
    <div style="flex: 1; display: flex; flex-direction: column;">
        <img src="https://github.com/user-attachments/assets/fb6af521-622e-45c6-bb5d-7c83c44ea667" alt="OLR_Actual_vs_Predicted_SIT" style="width: 100%; margin-bottom: 10px;"/>
        <img src="https://github.com/user-attachments/assets/df2baef5-082d-4116-992a-a9d2b27717d4" alt="OLR_Residuals_SIT" style="width: 100%;"/>
    </div>
</div>

-- The atmospheric indices are independent of each other (No Multicollinearity).

**REGRESSION AND RESIDUAL PLOTS:**
-- “All features” line fairly tracks the actual SIT, indicating that the model using all predictors together provides a reasonable prediction of SIT. Except at certain instances such as 1991-92, 2002 and 2010. 
-- When we exclude SOI or ZW3 and at some instances even ASL, the predicted values deviate more from the actual SIT, showing that these indices have a significant role in explaining SIT variation. Similar results seen for the Residual Plots. 
-- There are periods where the residuals are larger, indicating the model's prediction errors increase during certain years. 

<br><br>

III. **Dynamic vs. Thermal Drivers:** SIT is primarily influenced by dynamic atmospheric factors, whereas SIC patterns are more strongly affected by thermal processes like sea surface warming and ice melt.
   
<img width="1152" alt="image" src="https://github.com/user-attachments/assets/310d52c2-7592-4541-8a4c-e70569bde651">

Negative SAM patterns for SIT. For SIC, it seems like a reminiscent of ZW3 pattern or an ASL pattern. 
Positive SST-SIT relations--> increasing temperatures resulting in increasing SIT --> thermal component may not be that active. Opposite for SIC. 

**For e.g., Weddell Sector:** A negative relationship with winds--> Negative meridional wind anomalies (warm northerly winds) causing thicker ice --> due to convergence and compaction of ice against the coasts. (Dynamic?)Opposite for SIC: Warmer northerly winds from the lower latitudes would increase the near surface temperatures and consequently the melting of ice. The mechanical effect of the winds would push ice southwards, decreasing the SIC by melting (thermal effects) but making the ice thicker due to convergence. 

<br><br>

## References: 

•	Trivedi, S., Hobbs W., Raphael, M.N., “An Assessment of Antarctic Sea-ice Thickness in CMIP6 Simulations with Comparison to the Satellite-based Observations and Reanalyses”, 2024, The Cryosphere [Under review] <br>
•	Trivedi, S., Goyal, R., Raphael, M.N., “Extremes in Southern Hemispheric Zonal Wave-3 and their Impact on Antarctic Sea-ice Thickness”, 2024, Geophysical Research Letters [In prep]


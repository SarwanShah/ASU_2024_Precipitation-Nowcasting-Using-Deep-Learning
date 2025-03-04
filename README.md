# Summary

Implemented state-of-the-art ConvLSTM and TrajGRU models for precipitation nowcasting, leveraging satellite data with higher spatial (4 km x 4 km) and temporal resolution (15 min) . Created datasets of 1,560 and 779 sequences to train and test. Achieved RMSE of 3.69 mm/hr with 2-hour lead time and RMSE of 8.06 mm/hr with 4-hour lead-time

# Abstract

Precipitation nowcasting for short-term
storm forecasting (0–6 hours) is essential for timely
severe weather warnings. Traditional methods such as
numerical weather prediction (NWP) and radar extrapolation, often lack accuracy at short scales and are
computationally intensive. Recent deep learning models,
such as ConvLSTM and TrajGRU have offered promising
advances by capturing complex spatiotemporal dynamics.
This paper aims to evaluate these models on satellite data,
addressing the limitation posed radar’s limited global
coverage, while focusing on the region of Sindh, Pakistan
— a region with minimal meteorological infrastructure.
Thus, by contributing towards the improvement of global
nowcasting capabilities this work addresses critical forecasting needs heightened by climate change.

**REPORT**: [Final_Report.pdf](Paper/EEE598_Final_Paper.pdf)  

**Sample Test Result: Target (Left) vs Prediction (Right)**

<img src="Sample%20Test%20Result%20Gifs/1_ConvLSTM_2hr.gif" alt="Sample Test Result GIF" width="800">


# Poster
![Poster Presentation](Poster%20Presentation/poster.png)


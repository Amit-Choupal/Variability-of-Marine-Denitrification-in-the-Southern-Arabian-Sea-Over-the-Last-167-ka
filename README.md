# Variability-of-Marine-Denitrification-in-the-Southern-Arabian-Sea-Over-the-Last-167-ka
This project investigates variations in marine denitrification in the southern Arabian Sea over the last ~167,000 years using sedimentary δ¹⁵N records. We compare δ¹⁵N fluctuations with Marine Isotope Stages and Total Nitrogen (TN) to examine whether warmer periods and higher biological productivity were associated with stronger denitrification.

# Project Overview

Denitrification is an important process in the marine nitrogen cycle in which microorganisms convert nitrate into gaseous nitrogen under low-oxygen conditions.
The Arabian Sea contains one of the world's major oxygen minimum zones (OMZs), making it an important region for studying past changes in denitrification.
Nitrogen isotopes provide a way to investigate these changes. In particular, δ¹⁵N (delta-15N) preserved in marine sediments can record changes in nitrogen cycling and water-column denitrification.

In this project, I analyze a ~167,000-year marine sediment record from the southern Arabian Sea to investigate:
1. How δ¹⁵N changed through time.
2. Whether higher δ¹⁵N values occur during warmer Marine Isotope Stages (MIS).
3. Whether climate-related changes in marine productivity may have contributed to variations in denitrification.
4. Whether the relationship between productivity and denitrification changed between warm and cold climate intervals.

A simplified mechanism investigated in this project is:

Warmer climate / stronger summer monsoon
           ↓
Stronger upwelling
           ↓
Greater nutrient supply
           ↓
Higher phytoplankton productivity
           ↓
More organic matter exported to deeper water
           ↓
Greater microbial oxygen consumption
           ↓
Stronger oxygen depletion / intensified OMZ
           ↓
Enhanced denitrification
           ↓
     Higher δ¹⁵N

This provides a possible connection between climate, biological productivity, oxygen availability and marine nitrogen cycling.

# Dataset Aquisition and Description
The dataset used in this project is:
Singh, Dharmendra Pratap (2026). δ¹⁵N and TN records of sediment core SSD004 GC11. PANGAEA.
DOI: 10.1594/PANGAEA.993903

The record comes from marine sediment core SSD004 GC11 in the southern Arabian Sea and covers approximately the last 167 ka (thousand years).

Denitrifying microorganisms preferentially consume the lighter nitrogen isotope, ¹⁴N, leaving the remaining nitrate relatively enriched in ¹⁵N. Therefore, increased δ¹⁵N in marine sediment records can be used to investigate periods of enhanced water-column denitrification.

Total nitrogen (TN) represents the amount of nitrogen preserved in the sediment. It can provide a productivity-related nitrogen signal, although TN is not a direct measurement of primary productivity.

# Methodology
1. Data preparation: The .tab file was imported using Python and pandas.The relevant variables were extracted:

Age [ka BP], δ15N bulk [‰ air], TN [%]
Missing values were removed before analysis.

2. δ¹⁵N through time: The first analysis examined the variation of δ¹⁵N through the ~167 ka record.
A time-series plot was created with:

Age on the x-axis, δ¹⁵N on the y-axis, Marine Isotope Stages shown as background intervals
This allows changes in the nitrogen isotope record to be compared with major glacial and interglacial climate phases.

3. MIS comparison: The δ¹⁵N record was compared with broad Marine Isotope Stage intervals:

MIS 1 
MIS 2
MIS 3
MIS 4
MIS 5a
MIS 5b
MIS 5c
MIS 5d
MIS 5e
MIS 6

MIS 5 was separated into its major substages because it contains alternating relatively warm and cold intervals.The mean, median and standard deviation of δ¹⁵N were calculated for each interval.

4. δ¹⁵N and TN relationship: A scatter plot of:

δ¹⁵N vs TN
was created to investigate whether the denitrification-related signal showed a simple relationship with sedimentary nitrogen accumulation.

Pearson correlation was also calculated.
The whole-record correlation was: r = −0.123, This indicates a very weak negative linear relationship between δ¹⁵N and TN across the entire ~167 ka record.

Therefore, the relationship between nitrogen accumulation/productivity and denitrification is not a simple linear relationship across the complete record.

# Findings and Results
1. δ¹⁵N shows substantial variability through time: The δ¹⁵N record varies approximately between 4.7 and 8.8 per mil. The variations are not random. Several major changes occur on timescales comparable to the glacial–interglacial climate cycles.Some warm intervals show relatively high δ¹⁵N values, while several colder intervals show lower values.

2. Warm intervals generally show elevated δ¹⁵N: The comparison with MIS intervals suggests that several warmer intervals are associated with relatively high δ¹⁵N values.This is particularly noticeable when looking at the alternating MIS 5 substages.

This pattern is consistent with enhanced denitrification during some warmer climate phases. However, the relationship is not perfect. MIS 6, for example, also contains relatively high δ¹⁵N values despite being a glacial interval.

Therefore: Climate state appears to influence denitrification, but it is unlikely to be the only control.

3. δ¹⁵N and TN do not show a simple whole-record correlation: The δ¹⁵N–TN scatter plot produces a correlation coefficient of approximately: r = −0.123, this means that increased TN does not automatically correspond to increased δ¹⁵N across the entire record.

This is an important result because it suggests that, productivity-related nitrogen accumulation and denitrification were not coupled in the same way throughout the entire 167 ka record.

''The relationship may instead depend on climate state, ocean circulation and oxygen availability''

# Discussion

The observed increase in δ¹⁵N during several warm intervals can be explained by the relationship between the Indian monsoon, productivity and the Arabian Sea oxygen minimum zone.

During periods of stronger summer monsoon activity, stronger winds can enhance ocean upwelling. Upwelling brings nutrient-rich deeper water toward the surface, supporting phytoplankton growth. Higher biological productivity produces more organic matter. As this organic matter sinks and is decomposed by microorganisms, oxygen is consumed from the surrounding water.

This can strengthen oxygen depletion within the Arabian Sea OMZ.

Low-oxygen conditions favor denitrification, during which microorganisms convert nitrate into gaseous nitrogen. Because denitrification preferentially removes ¹⁴N, the remaining nitrogen becomes relatively enriched in ¹⁵N.

This provides a possible explanation for the observed:

Higher productivity → greater oxygen consumption → stronger oxygen depletion → enhanced denitrification → higher δ¹⁵N relationship during some warm intervals.

However, the weak overall δ¹⁵N–TN correlation shows that this mechanism does not operate identically throughout the entire record.

During colder periods, biological productivity can still be maintained through winter-monsoon-driven mixing and nutrient supply. At the same time, stronger mixing can improve subsurface oxygen ventilation. Therefore, relatively high productivity does not necessarily result in equally strong denitrification.

This provides a possible explanation for why TN and δ¹⁵N do not show a strong positive correlation across the complete record.

# Conclusion

This analysis indicates that δ¹⁵N preserved in the SSD004 GC11 sediment core records substantial changes in marine nitrogen cycling over the last ~167 ka. Higher δ¹⁵N values occur during several warm climate intervals and are consistent with periods of enhanced water-column denitrification.

The observed pattern can be explained by a possible connection between:

Summer monsoon → upwelling → productivity → organic matter export → oxygen consumption → OMZ intensity → denitrification → δ¹⁵N

However, the weak whole-record correlation between δ¹⁵N and TN (r = −0.123) indicates that productivity and denitrification were not simply coupled throughout the entire record.

"This suggests that climate state, monsoon seasonality, ocean ventilation and oxygen availability may have controlled the relationship between productivity and denitrification"

--------------------------------------------------------------*----------------------------------------------------------------------

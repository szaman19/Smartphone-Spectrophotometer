# Smartphone Spectrophotometer

The purpose of this project is to be able to detect chlorophyll and CDOM (Colored Dissolved Organic Materials) in water using a smartphone and a secchi disk only. 

The general procedure to measure the concentrations is to take two images of the secchi disk submerged and unsubmerged in water and compare the pixel data. 

The pixel-concentration model is based on solving the rendering equation in combination with the Beer-Lambert Law. In general, the modified rendering equation is inverted to get the concentration values per intensity ratio which is then used in the pixel-intensity equation to find concentration per pixel ratio per channel. The normalization factors for various different smartphone hardware must also be considered. 

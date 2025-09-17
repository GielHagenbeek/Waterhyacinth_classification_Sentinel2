# Water hyacinth classification

A google Colab script to classify the coverage of water hyacinths in rivers. Both spatial and seasonal varieties can be classified, using Sentinel-2 imagery.

## Abstract
Rivers are major pathways for plastic pollution entering the ocean, particularly in tropical regions. Tropical rivers are also exposed to invasive water hyacinths (WHs), which can entangle macroplastics, as found in the Saigon River, Vietnam, and may serve as a proxy for detecting plastic pollution using remote sensing. This study explores the transferability of that phenomenon, and two detection models, to Thailand’s Chao Phraya River. Over 62 km, an average of 32\% of floating plastics were inside WHs, with local trapping up to 78\%. While trapped proportions decreased downstream, plastic concentration per WH area was on average 59 times higher than open water. Sentinel-2 proved accurate for WH detection, though cloud cover limited use. Object detection transferred well for WHs (mAP50 = 68\%, -2\%) and entangled plastics (mAP50 = 54\%, +2\%), but poorly for free-floating plastics (23\% vs. 48\%). Physical sampling found 14 times more items than imagery, emphasizing WHs’ trapping role and proxy potential for monitoring riverine plastics and targeting clean-up.

## Data availability
This script uses Sentinelhub API and Sentinel-2 Surface Reflectance data.
To run this script, a Sentinelhub + Google Colab account is required. Additionally, uploading a shape file of the AoI (Area of Interest) is required.

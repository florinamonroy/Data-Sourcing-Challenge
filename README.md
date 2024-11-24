# Data-Sourcing-Challenge
Background
Illustrates preparation of a dataset for a prediction system that helps the [NOOA Space Weather Prediction Center]https://www.swpc.noaa.gov/about-space-weather  predict Geomagnetic Storms (GSTs).

These storms are caused by so-called Coronal Mass Ejections (CMEs), which are a massive bursts of plasma emitted from the Sun in irregular intervals, that Earth's magnetic shield fortunately renders harmless to us. However, this interaction with the magnetic shield can still create Geomagnetic Storms (which also cause the Northern and Southern Lights) that can be harmful to electronic devices such as satellites, GPS systems, and essential parts of our powergrids.

NASA and the Space Weather Prediction Center operate a number of measuring satellites that collect data on CMEs. This data is then used to warn powergrid operators and GPS system operators ahead of time, so that they can make necessary adjustments.

These videos from the Space Weather Prediction Center provide more information on the topic:
[An Introduction to Space Weather and the Space Weather Prediction Center](https://www.youtube.com/watch?v=JncTCE2NWgc)

and
[Space Weather Impact on the Power Grid](https://www.youtube.com/watch?v=caHYgTf6tO8)

However, these predictions are far from perfect, as you can see from this table showing the prediction accuracy of the forecasters responsible for [NOAA’s Space Weather Prediction](https://performance.commerce.gov/KPI-NOAA/NOAA-Geomagnetic-storm-forecast-accuracy-/bnak-2vs9/data)

For this purpose, data is extracted from the NASA API, specifically from two sources—its GST data and its CME data—then merged the data together and compute the average time it takes for a CME to cause a GST. Later, this data can be used with Machine Learning models to create predictions.



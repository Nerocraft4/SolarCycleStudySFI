# The Solar Cycle(s): Bibliography review, data analysis and time series forecasting
This repository is intended to contain all surrounding documents to the final project for the Space Environment subject (MAST, UPC-ETAAC).

It has both the raw and the cleaned-up NOAA datasets on SFI (Solar Flare Index), as well as the python notebooks for the data processing and the analysis, and the final Word and PDF report.
I will probably attempt to publish this in my Medium page through Towards Data Science, since I'm a collaborating writer there. We'll see. In any case, it will have to wait until it is corrected. 

## Summary
As a summary of the work, here are the conclusions:

I believe we have been able to, even if briefly, cover most of the history and current investigation lines regarding the Solar Cycle. In this article we have also taken time to explore
the data ourselves, investigate and make some future predictions on the Sun’s activity for the following decades.

Studying the variability and unpredictability of the SF index was fascinating, and being able to represent data grouped by different time scales allowed us to both understand the
underlying trend and the quick variations of the phenomena.

The status of the dataset, unfortunately, was very poor. The data itself, provided by NOAA and Kandilli Observatory, is precious and given with extreme detail and accuracy. Still, it is
regrettable that it is provided in such a substandard shape and formatting. Luckily, this did not stop us from conducting the study, and we were able to provide a clean dataset for future
users to utilize in their investigations.

We were able to make some predictions using several time-series models. The ARMA proved unsuccessful (see Annex II), but SARIMA yielded exciting results, agreeing with renowned
institutions in the field. We were also able to theorize a mathematical model to represent the cycle’s long scale fluctuations with success.

As we mentioned at the beginning of the article, these predictions and models are based on indirect measurements, and not actually describing the internal movements of the Sun’s core
and magnetic field. For us to be able to make predictions with confidence, we would need to mathematically model those fluid interactions in the star’s nucleus as well as corona, which
is extremely complex as of today.
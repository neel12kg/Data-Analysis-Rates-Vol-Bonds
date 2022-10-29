# Data-Analysis-Rates-Vol-Bonds

An easy walk-through of statistical relationships between iShares 20+ Treasury (TLT), PIMCO Emerging Markets Bonds (EM Bonds), Rates volatility (ICE MOVE BofA),
and treasury market volume.

We plot the following:
- Looking at distribution of rates volatility (lognormal vs normal) (Density, box plots, histograms)
- Correlations between all TLT price, TLT volume, EM bonds and rates volatility
- Scatter distributions for relationships between TLT and EM Bonds
- Scatter distributions for relationships between TLT ($) and TLT volume
- Daily percentage change against rates volatility over time

Most use relatively common libraries such as Pandas, Numpy and Matplotlib, however, to make the last plot dynamic I've used Bokeh.

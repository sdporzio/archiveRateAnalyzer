# ArchiverRateAnalyzer
Analyzes channel data rate for the Slow Monitor

In order to use it source "sourceMe.sh". You must be in the ArchiverRateAnalyzer folder.
Run "extractRates.py" to get the rate for the channels and plotRates.ipynb (jupyter notebook) to plot data.

You have to change variables in these two files if you want different channels.
If you have problems send me an email. Or ask, if I'm around.

Prerequisites (as far as I remeber):
postgresql
psycopg2
numpy
pytz
VPN active (to have access to Fermilab)
pyROOT + ipython + jupyter (if you want to plot data with "plotRates.ipynb")

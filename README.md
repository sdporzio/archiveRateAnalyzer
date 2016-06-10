# ArchiverRateAnalyzer
Analyzes channel data rate for the Slow Monitor

In order to use it source "sourceMe.sh". You must be in the ArchiverRateAnalyzer folder.
Run "extractRates.py" to get the rate for the channels and plotRates.ipynb (jupyter notebook) to plot data.

You have to change variables in these two files if you want different channels.

For reasons of security, the password to access the database is not provided in the scripts. In order to have access you can either:
- Create a file called "password.txt" in "Modules/" which contains the password.
- Modify the value of the variable "npPassword" in "Modules/querySQL.py" to the database password.

If you have problems send me an email. Or ask, if I'm around.

Prerequisites (as far as I remeber):<br/>
- postgresql<br/>
- psycopg2<br/>
- numpy<br/>
- pytz<br/>
- VPN active (to have access to Fermilab)<br/>
- pyROOT + ipython + jupyter (if you want to plot data with "plotRates.ipynb")

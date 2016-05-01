# Southwest (WN) Point Value Userscript

The purpose of this simple script is to display the variable points per dollar
for a Southwest point redemption flight.

Currently, as of 5/1/2016, this range is 72-80 points per dollar.

According to [nsx@Flyertalk](http://www.flyertalk.com/forum/26549270-post18.html),
the number of points per dollar increases roughly every April.

To run this script, open the raw version of [script.js](https://raw.githubusercontent.com/no2chem/wn_pointsscript/master/script.js), and paste it into the console
window of your browser after you have done a fare search on Southwest.

The script will display a breakdown as shown below:
![breakdown](breakdown.png)

# Technical Details

This script extracts information already present on the page. The fare code is 
present in the HTML rendered by Southwest already and is available by inspecting
the source. All this script does is render it on the page and divide the points
per fare by the dollar amount. The script uses the existing copy of jquery that
Southwest uses.

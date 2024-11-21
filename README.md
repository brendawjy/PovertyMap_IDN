# PovertyMap_IDN

A very simple R practice of mapping poverty rate based on Indonesian provinces. I used ChatGPT to help of course. The data for poverty rate was taken from bps.go.id, the Indonesian National Statistics Bureau (BPS - the abbreviation in Indonesian). Currently the regularly (quarterly?) released data does not have data for Jakarta (the capital) and North Kalimantan (new province in 2015, i think). I took the figures for the two provinces independently by browsing "poverty rate Jakarta" and "poverty rate North Kalimantan". Both are still from BPS tho.

Be aware that province names in BPS data is kinda different from province names in the shape file, like the one from BPS are all in uppercase, and "Kepulauan" is shorten to "Kep." in the BPS data. I modified them first in excel, and I chose to uniform it into the province names in shape file, then i uploaded to R.

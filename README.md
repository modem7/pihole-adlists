# Pi-Hole blocklists

![GitHub last commit](https://img.shields.io/github/last-commit/modem7/pihole-adlists)
![Link Check](https://github.com/modem7/pihole-adlists/actions/workflows/linkcheck.yml/badge.svg)
[![GitHub last commit](https://img.shields.io/github/last-commit/modem7/pihole-adlists)](https://github.com/modem7/pihole-adlists)

This is a list with URLs for [PiHole](https://github.com/pi-hole/pi-hole) in order to block malware, phishing and spam domains. I also included the ad and tracking blocklists.

## To use this
Open the [blocklist](https://raw.githubusercontent.com/modem7/pihole-adlists/master/Blocklist.txt) and copy the entire thing. 

Once you've copied, go to Pihole > Adlists.

Copy and paste all the URLs at once into the "address" box, click "add", then update Gravity. 

![image](https://github.com/modem7/pihole-adlists/assets/4349962/438ff833-ae5f-4504-a836-a88a1b87232b)

Once Gravity is updated, that's all you need to do. 

![image](https://github.com/modem7/pihole-adlists/assets/4349962/c9a7ce05-359f-4764-a5f1-8abdf1e40106)

## Things to be aware of:

Please note, that the URL's included in this list are merely links to adlists, not specific blocking domains, as such, each URL included in here will be updated via Pihole. 

This repo will update each time I update my lists, but other than that, there is no automated way of keeping up to date with this repo. 

There is a github action to make sure each link listed in blocklist.txt is live, and if at some point in the future they stop working, I will remove the link to reflect this. 

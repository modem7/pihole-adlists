# Pi-Hole blocklists

![GitHub last commit](https://img.shields.io/github/last-commit/modem7/pihole-adlists)
![Link Check](https://github.com/modem7/pihole-adlists/actions/workflows/linkcheck.yml/badge.svg)
[![GitHub last commit](https://img.shields.io/github/last-commit/modem7/pihole-adlists)](https://github.com/modem7/pihole-adlists)

This is a list with URLs for [PiHole](https://github.com/pi-hole/pi-hole) in order to block malware, phishing and spam domains. I also included the ad and tracking blocklists.

## To use this
Open the [blocklist](https://raw.githubusercontent.com/modem7/pihole-adlists/master/Blocklist.txt) and copy the entire thing. 

Once you've copied, go to Pihole > Adlists.

Copy and paste all the URLs at once into the "address" box, click "add", then update Gravity. 

![image](https://user-images.githubusercontent.com/4349962/153099263-228b0823-cc8d-4efe-b272-fe72e80803a9.png)

Once Gravity is updated, that's all you need to do. 

![image](https://user-images.githubusercontent.com/4349962/153099774-7a7e5c98-9061-4e15-b65b-48a6858d865b.png)

## Things to be aware of:

Please note, that the URL's included in this list are merely links to adlists, not specific blocking domains, as such, each URL included in here will be updated via Pihole. 

This repo will update each time I update my lists, but other than that, there is no automated way of keeping up to date with this repo. 

There is a github action to make sure each link listed in blocklist.txt is live, and if at some point in the future they stop working, I will remove the link to reflect this. 

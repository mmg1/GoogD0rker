# GoogD0rker

## About
GoogD0rker is a tool for firing off google dorks against a target domain, it is purely for OSINT against a specific target domain. Designed for OSX, if you want to tweak it for Linux simply use sed: `sed 's/open/newbrowser/g' googd0rker > googd0rker-newbrowser`. It is modified from goohak by [crowdshield](https://github.com/1N3/Goohak).

### GoogleD0rker-TXT

GoogD0rker-TXT was written by [xt3rob](https://github.com/txt3rob/bugbountydork) has been merged into this repo to keep continuity, changes will be added to this over time to account for extra D0rks and features.

### GoogleD0rker-TXT - Setup
Install the pre-reqs which are the google library for python, also install python if you haven't already.
`pip install google`

### GoogleD0rker-TXT - Info
This will output all the google results for each of the tasks so you can hopefully find a vunerability. A 503 error means you need a new IP as google knows you're up to something!  This will output the results to files and then you can browse and see what you have found.

### GoogleD0rker-TXT - Usage

`googD0rker-txt.py -d example.com`

## GoogD0rker Usage

`/googd0rker.sh domain.com`


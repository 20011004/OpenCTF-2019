name: MegaHash302
category: crypto
author: AnthraX101
final score: 99 points


## Overview

This challenge asks you to attack a chained cipher that is a sequence of a large number of cryptographic hash algorithms. 

Connect to the web server. This challenge asks you to find a second preimage that matches a given hash value with an 128-bit iteration count.


## Build

Use Python 3.7 and either:
    pip install web.py==0.40-dev1
Or for Ubuntu/Docker:
    apt-get install -y python3-webpy 

## Run

Use RealWebServer.py, -not- WebServer.py. RealWebServer hardcodes the CSPRNG so different instances don't have different target hashes or iteration counts. RealWebServer also uses a substantially more efficient hashing algorithm.

Use python 3.7 only. 

#Resources

We're going to put up a bunch of links in here for your reference. Most of it will be with reference to stuff we discuss in class, some of it will be tangential.

Work in progress...



##References, Reading
---

In [A Mathematical Theory Of Communication ](http://cm.bell-labs.com/cm/ms/what/shannonday/shannon1948.pdf) Claude Shannon laid forth the idea that once information became digital, it could be transmitted without error. 

[A Symbolic Analysis Of Relays and Switching Circuits](https://www.cs.virginia.edu/~evans/greatworks/shannon38.pdf) This paper point out the identity between the two "truth values" of symbolic logic and the binary values 1 and 0 of electronic circuits. Shannon showed how a "logic machine" could be built using switching circuits corresponding to the propositions of Boolean algebra

[Uncovering Social relationships through smartphone probes](http://conferences.sigcomm.org/imc/2013/papers/imc148-barberaSP106.pdf) This paper does some good analysis on social groups based on networks their phones are probing for.

##Tutorials, Software
---
[Wigle DB](https://wigle.net) : Crowdsourced war driving



###Networking
[Wire Edit](https://wireedit.com/) : Text editor for network stuf

[WireShark](https://www.wireshark.org/) : Classic network protocol analyser

[Debookee]([http://www.iwaxx.com/debookee/): Traffic interceptor

[Scapy](http://www.secdev.org/projects/scapy/) : Python networking framework

[Libtins](http://libtins.github.io/) : C++ networking framework

[libpcap tutorial](http://eecs.wsu.edu/~sshaikot/docs/lbpcap/libpcap-tutorial.pdf) : Not for the faint hearted

[N.S.Heyyy](https://github.com/antiboredom/nsheyy_gui/releases): Wi-Fi Sniffer

###Software Defined Radios	
[Primer](https://github.com/samatt/ArtSec-SDR)

[GnuRadio](http://gnuradio.org/redmine/projects/gnuradio/wiki)
	
###GSM
[OsmoBTS with USRP1](http://scriptogr.am/samatt/post/running-osmobts-with)

[YateBTS with BladeRF](http://scriptogr.am/samatt/post/running-yate-bts)

##Submarine Cables
---
[Telegeography's Submarine Cable Map](http://submarinecablemap.com)

[geojson of the Telegeography data](/march25/submarine_cables.geojson) : converted from a Google Fusion Table, which, I can't even

[*Private Line* Point Arena article from 1995](https://www.dropbox.com/s/ejdbrs9r4kf9mrq/private_line.pdf?dl=0)

[FCC Submarine Cable Licenses 1994-2001)](/march25/fcc) : attempt to narrow documents to submarine cables only; if interested in full FCC license archive (which has other cool satellite and international network stuff) will add to the repo

[Submarine Cable Taps](http://lifewinning.com/submarine-cable-taps)

##Other Cable/Physical Infrastructure Resources
---
[325 Hudson](https://gumroad.com/l/325Hudson)

[Seeing Networks in New York](http://seeingnetworks.in/nyc)

[Level 3 Cable Map](http://maps.level3.com)

[Traceroute Adventures with James Bridle](https://stml.makes.org/thimble/how-to-see-through-the-cloud)

[Slightly dated guide to major carrier hotels and telecommunications infrastructure in New York](http://cromwell-intl.com/travel/usa/new-york-internet/)

##Geodata and Mapmaking Resources
---

###General Educational Resources
[mapschool.io](http://mapschool.io) : a good overview for understanding conceptual basics of mapping, especially for the web.

[Maptime](http://maptime.io) : worldwide network of groups creating educational content about mapmaking, have a ton of [educational resources](http://maptime.io/lessons-resources/) online

###Editing Resources/Make a map hella fast
[geojson.io](http://geojson.io) : useful service for quickly visualizing, editing, and storing data in geojson format

###Converting File Formats
[gpsbabel](www.gpsbabel.org) : tool for converting geodata file formats, has a GUI and command line utility; there are a few wrappers for other languages out there also. 

[ogr2ogr](http://www.gdal.org/ogr2ogr.html) : a command line tool that's part of GDAL, possibly the most versatile and useful geospatial library ever. ogr2ogr is specifically useful for converting file formats

[togeojson](http://mapbox.github.io/togeojson/): converts KML and GPX to geojson

[joiner](https://github.com/mhkeller/joiner) : node module for doing equivalent of table joins between json and geojson data. 

# Introduction
This repository contains a dump of all entries from the European vulnerability database (EUVD), publicly hosted by the
European Union Agency for Cybersecurity (ENISA).

The main identifier for entries in the EUVD is a EUVD-ID, contrary to the CVE-ID. Most events contain a CVE-ID as well though.

The repository contains two types of files using the same directory strucutre as in the CVEProject (https://github.com/CVEProject/cvelistV5):
- euvd/<year>/<id-part>/<EUVD-ID>.json
- cves/<year>/<id-part>/<CVE-ID>.json

As not all EUVD entries contain a CVE-ID mapping, there are more entries in the resulting euvd folder than there are in the cves folder.

# References
- https://euvd.enisa.europa.eu
- https://euvd.enisa.europa.eu/apidoc

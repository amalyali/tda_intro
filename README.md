# Time domain astrophysics resources

---

## Discovering new transients/ variables
A transient/ variable system may be reported to the community through:
- Transient Name Server ([TNS](https://www.wis-tns.org/))
- Astronomers Telegrams ([ATels](https://www.astronomerstelegram.org/)) 
- General Coordinates Network ([GCNs](https://gcn.nasa.gov/); predominantly for GRB/ neutrino/ GW alerts)

and you can subscribe to these to get email updates about potential new sources worthy of follow-up. 
Alternatively, you may develop custom tools to identify interesting transients, such as through
interacting with alert brokers (e.g. [Lasair](https://lasair-ztf.lsst.ac.uk/) for ZTF allows for custom filtering scripts).

## Visual inspection
Visual inspection of the transient's position can be done through sky viewers (e.g. does the optical counterpart look like it's of Galactic origin?)
- [Aladin](https://aladin.cds.unistra.fr/AladinLite/), 
- [Legacy DR10](https://www.legacysurvey.org/viewer-dev/?ra=30&dec=-30&layer=ls-dr10&zoom=3)

## Data access
We also want to include multi-wavelength information to further constrain the physical properties of the transient. 
To do this, we inspect the multi-wavelength time-series data available for the system. For optical:
- [ASASSN](https://asas-sn.osu.edu/) (all-sky, but shallower)
- [ATLAS](https://fallingstar-data.com/forcedphot/) (only down to -50)
- [Gaia](http://gsaweb.ast.cam.ac.uk/alerts/search) 
- ZTF public lightcurves via [ALeRCE](https://alerce.online/) / [Lasair](https://lasair-ztf.lsst.ac.uk/); [ZTF forced photometry](https://ztfweb.ipac.caltech.edu/cgi-bin/requestForcedPhotometry.cgi) server

Mid-infrared:
- NEOWISE 

X-ray:
- X-ray upper limit servers (provides a history of past X-ray detections): [HILIGT](http://xmmuls.esac.esa.int/upperlimitserver/) 
- Chandra: [download via chaser interface](https://cda.harvard.edu/chaser/)
- NICER: [download via HEASARC interface](https://heasarc.gsfc.nasa.gov/db-perl/W3Browse/w3table.pl?tablehead=name%3Dnicermastr&Action=More+Options)
- XMM: [download via XMM science archive](https://nxsa.esac.esa.int/nxsa-web/#search)
- XRT: [download via Swift XRT data centre](https://www.swift.ac.uk/swift_portal/), [automated XRT image, spectra, lightcurve product generation](https://www.swift.ac.uk/user_objects/) 

---
## Additional material
- [Time domain astronomy taxonomy- what are the different types of transients?](https://github.com/profjsb/timedomain-taxonomy)
- Caltech [X-ray astronomy club lecture series](https://sites.astro.caltech.edu/~srk/XC/)



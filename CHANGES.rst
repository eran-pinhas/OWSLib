Changes
=======

0.17.0 (2018-09-04)
-------------------

- Fixed test-suite and converted doctests to unit-tests (#339).
- Support for OWS Context (#483 thanks @allixender)
- Support for WCS 2.0.0 and 2.0.1 (#430, thanks @doclements)
- numerous bug-fixes, especially for WPS.

0.7 (2013-02-18)
---------------

- Support for SOS 1.0.0, SOS 2.0.0, SensorML (thanks @kwilcox)
- Support for TMS (thanks @cleder)
- numerous bug fixes

0.6 (2012-12-22)
----------------

- Support for WMTS (thanks @bradh)
- packaging support (thanks @kalxas) for:
 - openSUSE
 - Debian
- addition of owslib.__version__
- ISO support:
 - multiple gmd:identificationInfo elements
 - gmd:distributorInfo elements
- WMS
 - read additional Layer attributes (thanks @elemoine)
- numerous bug fixes

0.5 (2012-06-15)
----------------

- Support for the following parsers:
 - WPS 1.0.0
 - WFS 1.1.0
 - CRS handling
  - URNs
  - URIs
  - EPSG:xxxx style
- etree.py looks for lxml.etree first now
- catch WMS service exceptions on GetCapabilities
- CSW exceptions are now Pythonic

0.4 (2011-10-02)
----------------
- Support for the following parsers:
 - CSW 2.0.2
 - OWS Common 1.0.0, 1.1.0, 2.0.0
 - Filter Encoding 1.1.0
 - ISO 19115:2003
 - FGDC CSDGM
 - NASA DIF
 - Dublin Core
 - WFS 2.0
 - WCS 1.1
- New SCM/bug/mailing list infrastructure
- Sphinx documentation

0.3 (2008-05-08)
----------------
- WCS support.
- Support for basic authorization in WMS requests (#107).

0.2.1 (2007-08-06)
------------------
- Added support for Python 2.5.
- Fixed ticket #105: Don't depend on Content-length in the http headers for
  getfeature.

0.2.0 (2007-02-01)
------------------
- Change license to BSD.
- Added service contact metadata.

0.1.0 (2006-10-19)
------------------
- New and improved metadata API.
- Wrappers for GetCapabilities, WMS GetMap, and WFS GetFeature requests.
- Doctests.

0.0.1 (2006-07-30)
------------------
- Brought OWSLib up out of the PCL trunk into its own space.
- Updated the testing frameworm.
- Initial test coverage:

 Name   Stmts   Exec   Cover   Missing
====== ======= ====== ======= =========
wms       105     68     64%     36, 41-48, 61-63, 114-118, 125-155, 172, 203-205
wfs        74     69     93%    146, 166, 199-201
wmc       111      0      0%     33-220
TOTAL     290    137     47%
====== ======= ====== ======= =========

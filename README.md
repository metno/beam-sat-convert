ICE-ARC project readme
----------------------
By Mikhail Itkin

This is a repository for ICE-ARC related work at Met.no


AVHRR conversion
----------------

To convert AVHRR L1B data obtained from CLASS archive I am using BEAM software, which has a Python 2.7 API.
To use BEAM one first has to export few shell variables, which are declared in the lib/beam.env

Software prerequisites
----------------------

 * Java JDK. Using Java Oracle JDK 7. (package from webupd8 works just fine)
 * JPY bidirectional Python bridge. See the [docs](http://jpy.readthedocs.org/en/latest/install.html)
 * BEAM. Using BEAM-5.0.
 * Beam Python Api (beampy). Provided with the BEAM package.

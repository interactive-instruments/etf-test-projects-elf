# ETF test projects for ELF
ETF test projects for use in [SoapUI](http://www.soapui.org) to test services against ELF extensions to the INSPIRE Technical Guidance requirements.

The ETF allows for testing geospatial webservices (like WMS, WFS, Atom) and XML files (like GML, GMD) to the requirements of the INSPIRE Technical Guidances for View and Download Services as well as the INSPIRE Data Specifications.

The ETF uses SoapUI [4.6.4](http://dl.eviware.com/list_soapui2.html) for test execution against Web Services and BaseX for tests against XML documents. SoapUI has a GUI and a command line interface. 

Tests for INSPIRE Technical Guidance for View and Download Services are available [here](https://github.com/Geonovum/etf-test-projects-inspire). This repository contains additional tests for additional ELF requirements specified in the [ELF specifications](http://elfproject.eu/documentation/specification).

As part of the work in the European Location Framework project [(ELF project website)](http://www.elfproject.eu/), a [web application](http://services.interactive-instruments.de/etf-demo-1-e) is available to run these tests.

This repository contains the code of any ELF-specific test projects.

## SoapUI workspace
To open the workspace with all test projects click on _File_ -> _Switch Workspace_ in the GUI and select the file _Test_projects_for_ELF-soapui-workspace.xml_.

## Execute tests in soapUI
The tests import additional libraries that are required to run the tests in SoapUI. Download the [required latest etf-owsgtl libraries](https://services.interactive-instruments.de/etfdev-af/etf-public-releases/de/interactive-instruments/etf/). If you are asked for a login use: etf-public-releases/etf-public-releases. Afterwards copy the content of the zip to the bin/ext sub folder of your SoapUI installation directory.

## Issues and feedback
Bugs, feedback or other issues about the testprojects? Please use the [issues system](https://github.com/interactive-instruments/etf-test-projects-elf/issues).

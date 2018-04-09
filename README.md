# RATIONALE #

This document describes the steps done to get IMHICIHU's hardware database
![hardware_database.png](https://bitbucket.org/repo/8zz7794/images/1191514673-hardware_database.png)

### What is this repository for? ###

* Quick summary
	- Creation of hardware database with open-source tools
* Version
	- 1.0

### How do I get set up? ###

* Summary of set up
	- [OpenOffice](https://www.openoffice.org/es/descargar/)
	- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
	- [HWiNFO](https://www.hwinfo.com/): hardware system information gatherer for Windows and DOS
* Configuration
	- Install the above 3 tools
	- run HWiNFO in every pc that need to be gathered. Once done this procedure, export the report in `.html` format
	- Once data is collected with HWiNFO, export in `.html` format 
	- process them with [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
	- once processed, give it a proper formatting inside OpenOffice, meeting your agenda
* Dependencies
	- a Windows operating system installed, and running in steady mode
* Database configuration
	- format the data according your goals


### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
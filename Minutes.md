
# 2nd Technical Working Group Meeting
## Minutes EMODnet Technical Working Group, Genua, 05-07/07/2017


**Day I**
### Introduction
* FSD welcomes all participants and thanks Antonio Novellino (AN) and ETT as local host
* Presentation agenda by FSD
* AN announces practical arrangements.

Participants: Jan Bart Callewaert (JBC), Pascal Derycke (PD), Thomas Loubrieu (TL), Mickael Treguer (MT), Nick Earwaker (NE), Alex Barth (AB), Alessandro Pititto (AP), Greame Duncan (GD), Gerrit Hendriksen (GH), Fanny Lecoy (FL), Ulla Alanen (UA), Bjarni Pjetursson (BP), Florence Benezit (FB), Fabio Gennai (FG), Bart Vanhoorne (BV), Filip Waumans (FW), Patrick Gorringe (PG), Antonio Novellino (AN), Dick Schaap (DS), Matteo Vinci (MV), Francisco Souza Dias (FSD), Paolo D'Angelo (PD), Marco Alba (MA), Simon Claus (SC)

* Increase unique visitor Central Portal
* Catalogue developments
* Dissemination through twitter success
* News items should be sent to secretariat, can be used for general EMODnet dissemination
* Newsletter has 2000 contacts, twitter followers 1718
* Tomorrow presentation of updates by TrustIT

#### Update JBC secretariat:
1. New tender for secretariat (end of august): support (monitoring, communication, checkpoint work: contribute to EOOS with MB and EuroGOOS, move Atlas of the Seas to secretariat, supporting Technical working group meetings, (two technical meeting per year at least one physical meeting per year)
2. Good outreach: EMODnet mentioned 15 times during IOC meeting (PG)
3.Visit EMODNet to Mercator Ocean (Open call to participate)
	

## Demo catalogue and geoviewer (FSD)

- [ ] Update chemistry link to integrated Seabasin product (currently to old link)  (AB)
- [ ] Add Access to web coverage service in metadata (AP)
- [ ] Geology:currently repeat metadata+> static xml that we harvest for metadata (BP)
- [ ] Seabed habitats: move towards one product (GD)
- [ ] Replace metadata with description?
- [ ] Getlegendgraphic: Alex & Bart check how to implement (BV & AB)
- [ ] Getmapinfo of seabed habitats not working (VLIZ)
- [ ] Inform Iain about new viewer & possible problem with EEZ (SC)
### Query tool functionality
 * Move from discrete points to complete region
 * Add it in the gis viewer
 - [ ] Include selection layer in GIS viewer: link to query tool. (IDEA VLIZ)
 * Example [EMIS/Marineanalyst](http://mcc.jrc.ec.europa.eu/dev.py?N=simple&O=410&titre_page=EMIS-R%20Marine%20Analyst&titre_chap=Assessment%20tools)

### EMODnet Catalogue
####	EMODnet Biology
* Q : Link Atlas/European atlas of the seas?
* Q: Sealevel data?
* Q: Species distribution modelling: start with North Sea (suggestion DS)
#### EMODnet chemistry
* Q: Marine litter maps: under discussion in what format
- [ ] Map chemistry plots: deep links? (AB)
#### EMODnet physics (AN)
* Time dimension: 7 days, 60 d, 1Y, 10Y,
* Services: SOAP/Rest/OGC/THREDDS
* Geoserver: platform type, parameter, sea basin
- [ ] HF Radar, MEOP data: THREDD server: using OGC standard (VLIZ)
* Monthly averages, max,min: Temp, sal; sea level, Sea Ice, 
- [ ] AN provide Xml metadata per platform (AN).
#### EMODnet Seabed habitats
* Q: OSPAR declining habitats: link with ICES Vulnerable habitats
* Provide WPS?
- [ ] Move from mapserver to Geoserver/PostgreSQL (GD)
* Geoserver app-schema: translate between schemas (INSPIRE)
*	Track WMS requests?
*	Central chat/discussion: slack?
- [x]	Setup EMODnet Github (VLIZ)
####	EMODnet Geology
* Map powered by EGDI
*	Projection EPSG:3034 (For European datasets)
*	Products in PostgreSQL
*	Web tool (charts, cookie consent, captcha) : not available
*	EMODnet wish list:
  1. General terms of use (?)
  2. Single sign on (Thomas)
  3. User feedback & help desk: (secretariat, CP)
  4. Piwik (TrustIT)
#### EMODnet Bathymtry
- [ ]	Bathymetry's basemap as background layer CP (DS)
*	Updating pipeline
- [ ]	Getfeature info: colour	=> use WCS (VLIZ & GH)
#### EMODnet Human activities
*	IAS data: clean GB’s of data
*	Buy data or is provided for free

### Query multidimensional dataproducts 
#### GH presents
* Infoline.openearth.eu
* Nhi.nu/waterbodems
* Domain super-seeding data collection using services
*	Use case 1: Relation between depth and Amphiura f
* Depth: Python package: owslib – occurrences species
- [ ] Advertise services better (VLIZ)
- [ ] Code snippet (publish in EMODnet  Github) (GH)
- [ ] Create page describing WMS/WFS/WCS) (all lots) 
#### Multidimensional datasets AB presents
*	Present netCDF 4/Opendap
*	Oceanbrowser WMS (unit lacking)
*	Also has vertical sections (GIS systems need to consider 3D)
*	Legend: use OGC standards (SLD…): to discuss on github?


**Day II**

#### Open Sea Lab (Presentation by JBC)
* Selection procedure
- [ ]	**Prepare data packages (All)**
- [ ]	Select people to be part of tech assistance group (All)
*	Discussion on prices
#### Dashboard example physics (AN)
*	Using logs on webserver
*	Analyse logs (filter out bad suspect IP’s)
####	Dashboard example Ifremer (TL)
*	Analysis of products for MED checkpoints
*	Overview products per domain, per availability
*	Feedback loop to dataprovider?
*	Technical monitoring: semaphore
  1.	React to failure of services
  2.	Reporting to assess performance and availability
  3.	Metadata in sextant, icinga used to test, monitor
  4.	AtlantOS working group on usage logging
*	Dedicated feedback to data providers (who’s using their data)
*	Overcome dilution of data providers contribution (overview contributions per provider)
*	Raw logs (apache/ftp)
*	Request; user; dataset
#### Presentation EMODnet data ingestion (DS)
#### EMODnet progress indicators (FlB)
*	New progress indicators proposed
*	5 aspects: relevant, actionable, precise, easy to report, coherence
 ###### Indicators:
* 1: Volume and coverage of data and products (per theme/seabasin)
*	2: Coverage of acquired external data products per parameter
*	- [ ] Coordinators need guidance document with indicators partly completed per theme (FB)
*	3: Organisations supplying data/products
*	4: List quality and harmonization steps to make acquired: difficult!
*	5: Number of built own dataproducts
*	6: Visibility
*	7: Technical monitoring (visitor stats…)
*	8: Interfaces to access data (how to log WMS/WFS, how to compare between portals?)
*	9: Uses
*	10: Application, (used on services) 
*	List publications (bonus indicator)
#####	Discuss further at SC meeting, target: first delivery after Y1 contracts
- [ ]	Technical monitoring: website availability, responsiveness, mobile adaptability= > send dashboard link to coordinators: (FG)
- [ ]	Registration funnel: Piwik
- [ ]	Central Piwik installation – pilot with Geology
- [ ]	Possibly Central Piwik installation on CP server

####	Single sign-on (TL)
*	MarineID: used by SDN, Copenicus, EMODnet
*	3600 users
*	Link with B2Acess
*	Link with Copernicus MEMS, CMEMS, Mercator Ocean, EUMETSAT, EOSC
*	Collect basic authentication
*	Autorization/data licensing managed in different databases
*	Authorization/License: rights between marineID/EMODnet CP:
  1.	MarinID users can login into QueryTool 
 -[ ]  2. List & compare attributes between user databases (TL & BV)
* Ravamp Central Portal (FB)
  1.	Overall acceptance
*	Data policies
  1.	Map existing policies that exist and propose overall data policy EMODnet by next SC meeting (JBC)
*	Next meeting technical working group beginning 2018
*	FSD Thank all partners and meeting is closed



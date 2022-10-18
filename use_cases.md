# Geospatial – Use Cases 
 
### User(s)  
NHS Analyst, Ambulance Service Analyst, Policy Analyst 

### Use-Case 1 - Base maps of available public health-related API layers  
**Description:** Layers of available public data (through API or alternative) alongside current NHS geographical ontologies.  A user would be then able to quickly import their own LSOA level local/sensitive data and the standardise against these different layers before visualising.  This would allow a fast and common way of seeing inequalities and variation in geographical health metrics.

### Use-Case 2 – Calculating travel Times from/to services  
**Description:** Building on use-case 1, both and an aggregate calculation and visualisation of travel time from a list of services (e.g. GPs in an area, or a list of emergency services).  Include walk, drive, bus, tube etc...  Include time of day and traffic. First focus preferable on walking + bus, or public transport services and combinations. 

### Use-Case 3 - Allocating interim services 
**Description:** Building upon use-case 2, the user would be able to add (or possibly remove) service points and see the impact upon the aggregate metrics and visualise the new coverage map. Day-to-day for an analyst, this could be a location to send a temporary diabetes clinic out to the general population, think similar to a temporary blood donation clinic.  

### Use-Case 4 - LSOA Density of use of individual service 
**Description:** For a given catchment area and an identified service (e.g. an A&E) display an LSOA choropleth map of the density of usage.  This is expected to highlight areas of comparative high usage and would be able to track usage over time (by taking snapshots or having a temporal feature) to see the impact of additional services or policy changes on usage after the fact. Incorporated in this use-case is LSOA metrics but also ideally medical service capacity metrics, e.g. GP Capacity. 

### Possible milestones 
- not necessarily in order 
- Content to gain interest at nhs pycom talk on 16th.  
- Blog post(s) discussing use-case, features and requirements, technical considerations and choices of libraries/approaches. 
- Identification of ideal shape formation which supports NHS ontologies (including considering boundaries and aggregation) 
- Combination of travel networks (walking, driving, bus, underground) 
- Identification of publicly accessible and useful data 
- Mapping of data into LSOA layers 
- Efficient point to point travel calculations  
- Caching setup 
- Calculation of aggregate metrics for a geography  
- UI considerations and outreach 
- Amendment feature for adding artificial services 

#### Beyond scope possible use-cases 
- Causal/network analysis – Impactability of a new GP Practice on diabetes cases in a town/ region. 
- Trend analysis of services (Ambulance service Analyst examining demand on an A&E unit in a deprived area).  

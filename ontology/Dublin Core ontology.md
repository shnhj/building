The DUL (DOLCE+DnS Ultralite) ontology includes descriptions and situations ontology; the purpose of its reuse is to provide the related upper-level concepts , including the class PhysicalObject, which epresents any object that has a space region, and the object property 
hasLocation, which describes the spatial location of any entities. 

The data properties identifier and title for distinguishing each entity are reused from the widely-used Dublin Core Ontology , which also provides another concept: Location. 

To describe the location, a geographic coordinate point and/or a postal address can be used, whose vocabularies are, respectively, provided by the well-known WGS84 Geo Positioning Ontology and the website schema.org. 

The latter also contains a wide range of vocabularies for event escription. To represent the weather related to the location, the specific Weather Ontology (WO) provides the reusable patterns and terms.

Several ontologies have been found for building representation, such as the IFC2X3 – University of Ghent Ontology, the gbBuilding Information Ontology (BIO), the Architecture and Building Physics Information Ontology and the SimModel ontology .

Considering that the focus of the target ontology is the energy-related information, rather than the highly detailed building physics, the BIO ontology is a good choice. 

BIO provides a range of defined classes, axioms and datatypes for reuse, such as the Building, BuildingElement and uildingParameter. 

In addition, the Energy and Resource Ontology (ERO) is used to complete the energy information for buildings, since it provides various concepts for energy description, such as EnergyParameter, EnergyFacility, EnergyType, EnergySupply and EnergyTariff. 

With regard to the occupants in buildings, the concept OccupancyParameter is selected from the User Behaviour and Building Process Information Ontology (PO), which is an ontology used to represent the behaviours and processes involved in smart home systems.

To describe the observation of various parameters, the widely recognised W3C Semantic Sensor Network (SSN) ontology is selected. 

It provides a complete representation for bservations, 
including terms such as Observation, ObservationValue, FeatureOfInterest and Property. 

However, the SSN ontology has not included the time and unit domains, which are intended to be imported from separate ontologies. 

The well-known OWL-Time Ontology and the Ontology of Units of Measure (OM) are used, respectively, to describe the observation time and the unit of observation value.

Most importantly, to represent the KPI calculation, the ontologies related to mathematical modelling have been searched. 

The Mathematical Modelling Ontology (MAMO) provides 
concepts such as Mathematical_model, Variable, Independent_variable and Dependent_variable. 

However, MAMO is still unable to completely describe the KPI calculation. 

Therefore, the patterns of the Model ontology in the OntoMODEL (Ontological Mathematical Modeling Knowledge Management) ontology are also reused. 

This ontology represents the different components of the mathematical model, including the equation, assumption, variables and constants. 

Lastly, there are also some other ontologies which are not available on the Web but part of whose patterns have been used, such as the ontology to represent energy-related occupant behaviour in buildings, proposed by Tianzhen Hong et al., the CIM ontology proposed by Neumann et al. and the CIM extension of the microgrid energy management system proposed by Ming Ding et al.
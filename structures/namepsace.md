Sample Namespace that can be adopted for oil and gas, water/waste water, manufacturing, etc. 

It is important that the names and categories used to organize the first few levels of the namepace be driven by your business needs. If the categories do not apply to the business implementing the namespace then they will have a hard time adopting the data model into their business processes because that will make data hard to find! 

The overall structure should not become too deep. The goal is to enable users and other people to be able to find useful information. Forcing the structure to be at most 10 layers deep will assist people in finding what they need. 

It is helpful to note that this is the rough structure to assist with organization and to help us speak the same data language. If you need to add other objects to the structure make your particular project work (displays, graphics, etc.) please do. This is meant to be the base, other things can be layered on top. 

# Unified Namespace

* Level 0 - Area
  * Level 1 - Sub Area
    * Level 2 - Site/Location
	  * Level 3 - Building/Well/Equipment
	    * Equipment
			* Machine
			* Optimization App
			* Pump
			* Valve
		* ERP
		* IO
		  * Flow Switch A
		  * Pressure Transmitter 1
		  * Misc. Tags Go Here
		* MES
		* Meters
			* Gas Meter
		    * Water Meter
			* Power Meter
		* Tanks
			* Chemical Tank 1
			* Water Tank 2
			* Fuel Tank 3

## Level 0

This is a logical organizational unit. It helps if it represents a business unit, a country, a producing pool or basin or some other large encompassing category. 

Oil and gas applications typically benefit from having this level represent the business unit, basin or other large geographic division (North/South) at this level. 

## Level 1

This is a secondary organizational category. This might be a state, a province, a municipality, a sub-category under Level 0. 

Oil and gas applications would generally make this level represent a producing Field or Team. 

Water/Waste Water might make this level represent a neighborhood. 

## Level 2

With the larger categories out of the way, this level can represent physical locations or more specific buckets of data. Depending on the business or use case this might be a particular location (address, surface site) or it could represent a factory or refinery. 

For oil and gas we typically make this level represent a physical surface location. 

## Level 3

This level is for specific assets that are important to a particular business. Might be a well (W/WW or O&G), or a vehicle, or a particular unit in a manufacturing plant. 

At this level it makes sense to use more specific names as well. These names should reference the common name for an asset in the organization. 

## Level 4

This is where we have some standardized folders or structures that hold information about the asset. Here is a basic set of folders. 

* Equipment
* ERP
* IO
* MES
* Meters
* Parameters/Metadata (TODO: need to pick one or the other)
* Tanks

## Level 5

This level is for specific sub-equipment, meters, etc. that provide source data. Information contained in deeper levels is specific to this piece of equipment. Might be a meter, a tank, a part of a manufacturing line, or information coming off the plant floor. 

## Level 6-10

TODO: Need to fill out this description.  

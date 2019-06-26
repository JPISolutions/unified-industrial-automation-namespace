# Meter Namespace 

Use this structure at Level 5 in the namespace. 

Tag examples are provided for reference. Not all are required or applicable for different meter types. 

The configuration tag names were taken from the Realflo object in ClearSCADA. 

- [ ] Get input from community about historical volume tags. Should we be using Today (TDay), Yesterday (YDay), Current Day (CDay), or Previous Day (PDay)?
- [ ] Make a decision about abbreviating the tag names. 

Place at Level 

* Meter
  * Configuration
    * Meter configuration tags go here...
	* CompressibilityCalc
	  * Information related to AGA8
	* ContractBasePressure
	* ContractBaseTemperature
	* FlowCalculation
	  * Flow Calculation parameters go here...
  * IO
	* Meter Tags go here...
	* CDayVolume
	* DiffPress
	* FlowRate
	* FlowTemp
	* LHourVolume
	* PDayVolume
	* StaticPress
    * Other Tags go here...
  * Parameters
	* Metadata tags go here...
  

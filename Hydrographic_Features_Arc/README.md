# Hydrographic Features Line

### Summary  

PWD's Office of Watersheds has compiled a geodatabase of Philadelphia hydrographic features for Philadelphia County and its contributing watersheds. The data is comprised of a combination of USGS's National Hydrography Dataset stream flow data, planimetric data digitized by Sanborn in 2004, and data provided by PWD field survey work.  
Features updated:  09/26/2012  
Attributes updated: 09/26/2012  
Metadata updated  09/26/2012  
Update Frequency - monthly

### Description  

AbstractPolyline geometric features representing the center flow line of all waterways in Philadelphia's five major watersheds.Data DevelopmentInitial data was captured from orthoimagery flown in 2004 by Sanborn. A combination of automated feature extraction (Planimetrics), desktop digitization and field survey is the basis for this dataset which is updated regularly by PWD. As new orthoimagery reveals changes in stream geometry, adjustments are made to the polygon and line file to reflect reality. The resolution and accuracy of newer orthoimagery improve over time, allowing more detailed feature extraction.Office of Watersheds staff maintains the feature datasets regularly, making geometric and attribute changes or adding new streams or infrastructure. The database is setup to reflect various forms of infrastructure along streams such as culverts, bridges, dams, and channelized segments. Additionally, unique segment and reach IDs were added to correlate to PWD Fluvial Geomorphology stream studies. USGS NHD Stream Names and IDs have been carried over and stream order classifications using both the Shreve and Strahler methods are coded. See the tables below for more detailed attribute entity information.Key attribute field names and descriptionsCREEK_NAME - Name of WaterwayMUNI - Municipal BoundaryCOUNTY - County NameWATERSHED - Major WatershedSUBSHED - Subshed or BasinLABEL - Use field for map labelingSEGMENT_ID - ID to stream segment between cross sectionsREACH_ID - ID to stream reach half the distance to cross section upstream and downstreamFGM_CODE - FGM PrefixINF1 - Infrastucture types including; None(Natural Stream), Bridged, Culverted, Impoundment (Lake, Pond, Reservior) INF2 - Channelized stream: Yes, No INF3 - Downstream Channel Position including: Left Bank, Right Bank, Bottom, Both Banks, All Sides, Left Bank and Bottom, Right Bank and BottomINF4 - Type of ImpoundmentINF_ID - Corresponds to internal Infrastructure IDSOURCE - Source of Orthophotography or SurveyGNIS_NAM - Name of Waterway in NHDGNIS_ID - ID of Waterway in NHDMON_ID - Corresponds to internal Monitoring ID (upstream of Monitoring location)RESTORATION_ID - Corresponds to internal Restoration Project IDORDER_SHREVE - Stream Order - Shreve MethodORDER_STRAHLER - Stream Order - Strahler MethodUREACHID - Upper Reach IDFACILITYID - Facility IDEDITOR - EditorEDIT_DATE - Editor DateCoordinate systemNAD_1983_StatePlane_Pennsylvania_South_FIPS_3702_FeetProjection: Lambert_Conformal_ConicFalse_Easting: 1968500.000000False_Northing: 0.000000Central_Meridian: -77.750000Standard_Parallel_1: 39.933333Standard_Parallel_2: 40.966667Latitude_Of_Origin: 39.333333Linear Unit: Foot_US (0.304801)Geographic Coordinate System: GCS_North_American_1983Angular Unit: Degree (0.017453292519943299)Prime Meridian: Greenwich (0.000000000000000000)Datum: D_North_American_1983Spheroid: GRS_1980Semimajor Axis: 6378137.000000000000000000Semiminor Axis: 6356752.314140356100000000Inverse Flattening: 298.257222101000020000Thematic mapping LABEL - Use field for map labelingUnderlay this line file with Hydrographic_Features_PolyOther InformationFeel free to contact us with any questions or to point out errors.  

### Data Dictionary

| Field | Description  
| ----- | :----------:  
| FID |  
| Shape |  
| CREEK_NAME |  
| MUNI |  
| COUNTY |  
| WATERSHED |  
| SUBSHED |  
| LABEL |  
| SEGMENT_ID |  
| REACH_ID |  
| INF1 |  
| INF2 |  
| INF3 |  
| INF4 |  
| INF_ID |  
| SOURCE |  
| GNIS_NAME |  
| GNIS_ID |  
| MON_ID |  
| RESTORATIO |  
| ORDER_SHRE |  
| ORDER_STRA |  
| SHAPE_LEN |  


### Credits  

Philadelphia Water Department, Office of Watersheds  
1101 Market St. 4th Fl. Philadelphia PA, 19107  
215-685-6246  
maryellen.mccarty@phila.gov

### Use Limitations  

The City of Philadelphia makes no representation about the accuracy of any specific information in this GIS data and is provided as is and without Warranty of any kind. The user of this data will assume complete responsibility for any and all occurrences resulting from its use or display and will hold the City of Philadelphia harmless from any and all claims, demands, liabilities, obligations, damages, suits, judgments or settlements, including reasonable costs and attorneys' fees, that arise from use of this data.
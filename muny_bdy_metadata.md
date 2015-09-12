##Metadata for muny_bdy.geojson
Generated from St Louis County GIS Datawarehouse 2015-09-12 09:12  
Last updated 2015-08-09 22:15  
  
###Source  
Product of [St Louis County Dept of Planning](http://www.stlouisco.com/propertyandroads/countywideplanningpolicy#boundary) in conjunction with [St Louis Boundary Commission](http://www.boundarycommission.com/).  
  
###Processing  
Original data has been unprojected and reprojected from NAD_1983_StatePlane_Missouri_East_FIPS_2401_Feet [ESRI:102696](http://epsg.io/102696) to GCS_WGS_1984 [EPSG:4326](http://epsg.io/4326)  

    Original projection WKT:  
    PROJCS["NAD_1983_StatePlane_Missouri_East_FIPS_2401_Feet",GEOGCS["GCS_North_American_1983",DATUM["North_American_Datum_1983",SPHEROID["GRS_1980",6378137,298.257222101]],PRIMEM["Greenwich",0],UNIT["Degree",0.017453292519943295]],PROJECTION["Transverse_Mercator"],PARAMETER["False_Easting",820208.3333333333],PARAMETER["False_Northing",0],PARAMETER["Central_Meridian",-90.5],PARAMETER["Scale_Factor",0.9999333333333333],PARAMETER["Latitude_Of_Origin",35.83333333333334],UNIT["Foot_US",0.30480060960121924],AUTHORITY["EPSG","102696"]]  
    
    New unprojected coordinate system WKT:  
    GEOGCS["WGS 84",DATUM["WGS_1984",SPHEROID["WGS 84",6378137,298.257223563,AUTHORITY["EPSG","7030"]],AUTHORITY["EPSG","6326"]],PRIMEM["Greenwich",0,AUTHORITY["EPSG","8901"]],UNIT["degree",0.0174532925199433,AUTHORITY["EPSG","9122"]],AUTHORITY["EPSG","4326"]]  
    
Processing completed using FME Workbench version 2015.0 Build 15244  
  
###Fields  
Name: MUNICIPALITY 
Data Type: String  
Width: 50  
Description: Name of the municipality  
  
Name: MUNI  
Data Type: String  
Width: 3  
Description: Municipal alpha code. Used for identification in certain law enforcement and public works records  
  
name: MUNICODE  
Data Type: String
Width: 3  
Description: Zero-padded municipal numerical code. Used in [St Louis County Department of Revenue](http://stlouisco.com/YourGovernment/CountyDepartments/Revenue) and [St Louis County Assessor](http://stlouisco.com/YourGovernment/CountyAssessor) records to designate taxing municipality for a parcel.  
  
Name: LABELTEXT  
Data Type: Double  
Description: Enumeration of municipalities in alphabetical order. Used for labeling cites in mapping in conjunction with a numbered table in alphabeticla order.  
  
  

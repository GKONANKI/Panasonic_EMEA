# Panasonic_EMEA
Panasonic EMA repository
SAP BW Obsolete Calculated Key-figure (CKF) /Restricted Key-Figure (RKF) Identification.

For Calculated Key-figure (CKF) and Restricted Key-figure (RKF) Housekeeping, identify the list of obsolete CKF/RKFs which are not used in SAP BW Business Explorer Queries/Workbooks.

IBM AMS team developed a tool to identify list of obsolete CKF/RKFs which are not used in Queries. 

As a part of the solution, we have used SAP standard Function module - RSZ_DB_COMP_WHERE_USED to identify the Obsolete CKF/RKFs which are not used in Query, Workbooks.

CSV file will be generated with date and timestamp in Application server for further decision making for deletion of Obsolete CKF/RKFs. 


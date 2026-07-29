This Object Management Group (OMG) GitHub repository contains standard xml data dictionaries supporting the
Ground Data Delivery Interface (GDDI) specification located at: https://www.omg.org/spec/GDDI

These dictionaries provide Standard GDDI 'Types' and are individually version-controlled via the \<majorVersion\> and \<minorVersion\>
elements contained in each xml file (as explained in the GDDI specification).

This GDDI 'Type' version is also contained in each xml dictionary file name with the format:
gddi-standard-typeid-\<TYPE ID VALUE\>-\<TYPE NAME\>-v\<MAJOR VERSION\>.\<MINOR VERSION\>.xml

Default values for each Tag-Length-Value (TLV) are defined in the 'description' field of each dictionary via the following format:
"(Default: \<VALUE\>)", where the \<VALUE\> is parsed out by the receiving GDDI endpoint for the applicable TLV.

Any Vendor-specific GDDI data dictionaries are controlled at the vendor's discretion.

Vendors are identified by vendor identification numbers, which are defined in [gddi-vendors.md](gddi-vendors.md). 
These Vendor IDs are not required when using the 'standard' GDDI data dictionaries; 
they are only applicable when using vendor-specific GDDI extensions as described in the GDDI specification.

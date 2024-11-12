# GRIB2 CF-Names
This repository contains a list of GRIB2 CF-Names. The list is based on the [CF standard names table](https://cfconventions.org/Data/cf-standard-names/current/build/cf-standard-name-table.html). The list is used to map GRIB2 parameter keys to standard CF-Names.

The table is a CSV file with the following columns:
- discipline (GRIB2 discipline)
- parameterCategory (GRIB2 parameter category)
- parameterNumber (GRIB2 parameter number)
- cf_standard_name (CF standard name)
- cf_table_version (CF table version)

The table is found in `grib2_to_cf_conversion.csv`. The table itself is versioned adhering to the [Semantic Versioning](https://semver.org/) standard.

## A note on the GRIB2 standard
The GRIB2 standard is defined by the World Meteorological Organization (WMO). The standard is used to encode meteorological data.
Documentation and code tables for the GRIB2 standard can be found at the [WMO GitHub GRIB2 repo](https://github.com/wmo-im/GRIB2/tree/master).

- [Code Table 4.1](https://github.com/wmo-im/GRIB2/blob/master/GRIB2_CodeFlag_4_1_CodeTable_en.csv): Parameter category by discipline for GRIB edition 2.

- [Code Table 4.2](https://github.com/wmo-im/GRIB2/blob/master/GRIB2_CodeFlag_4_2_0_0_CodeTable_en.csv): Parameter number by discipline and parameter category for GRIB edition 2. Notice that there are subtables for each discipline.

- [Code Table 4.5](https://github.com/wmo-im/GRIB2/blob/master/GRIB2_CodeFlag_4_5_CodeTable_en.csv): Level types for GRIB edition 2.

### A short overview of more common keys

The table below shows some of the more common keys used within Numerical Weather Prediction in the GRIB2 standard.

| levelType  | Description                            |
|------------|----------------------------------------|
| 102        | Specific altitude above mean sea level |
| 103        | Specified height level above ground    |

# GRIB2 CF-Names
This repository contains a list of GRIB2 CF-Names. The list is based on the [CF standard names table](https://cfconventions.org/Data/cf-standard-names/current/build/cf-standard-name-table.html). The list is used to map GRIB2 parameter keys to standard CF-Names.

The table is a CSV file with the following columns:
- discipline (GRIB2 discipline)
- parameterCategory (GRIB2 parameter category)
- parameterNumber (GRIB2 parameter number)
- cf_standard_name (CF standard name)
- cf_table_version (CF table version)

The table is found in `grib2_to_cf_conversion.csv`. The table itself is versioned adhering to the [Semantic Versioning](https://semver.org/) standard.
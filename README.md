# kismet2report.py
Convert Kismetdb into KML Output or CSV output.  Allows for exclusion or inclusion of SSIDs for reporting.

## Prerequisites
`pip install -r requirements.txt`
or
`pip install simplekml`

## Usage
```
usage: kismet2report.py [-h] (-k | -c) -i INPUT -o OUTPUT [-f] [-E EXCLUDE | -I INCLUDE] [-v]

Convert Kismetdb into KML Output or CSV output. Allows for exclusion or inclusion of SSIDs for reporting.

options:
  -h, --help                       show this help message and exit
  -k, --kml                        Output as KML
  -c, --csv                        Output as CSV
  -i INPUT, --input INPUT          Input file
  -o OUTPUT, --output OUTPUT       Output file
  -f, --force                      Force Overwrite of Output file
  -E EXCLUDE, --exclude EXCLUDE    Comma Separated list of SSIDs to exclude
  -I INCLUDE, --include INCLUDE    Comma Separated list of SSIDs to include
  -v, --verbose                    increase output verbosity
```

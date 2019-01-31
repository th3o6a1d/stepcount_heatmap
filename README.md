# Visualize Step Count on Calendar Heat Map

- Visualize your Apple healthkit stepcounts as a calendar headmap. 

- Black square indicates 20,000 steps per day. 

![Step Count](https://raw.githubusercontent.com/th3o6a1d/stepcount_heatmap/master/StepCount.png)

## Citations: 

- https://github.com/markwk/qs_ledger/blob/master/apple_health/apple-health-data-parser.py for XML to CSV parser

- calmap python heatmap

## Usage

- Export your apple health data. `mkdir data`. Convert the data from xml to csv using `python3 parse_health.py <apple health data.xml>`. Put the exported csv files in the data directory.

- Start virtual python environment. `virtualenv apple_health; source apple_health/bin/activate`

- Install dependencies. Will need the usual stuff plus calmap package. `pip3 install requirements.txt`

- Start jupiter notebook. `jupyter notebook`
# Visualize Step Count on Calendar Heat Map

Visualize your Apple healthkit stepcounts as a calendar headmap. 

![Step Count]('/StepCount.png')

Citations: 

- https://github.com/markwk/qs_ledger/blob/master/apple_health/apple-health-data-parser.py for XML to CSV parser

- calmap python heatmap

## Usage

`virtualenv apple_health`

Start virtual environment

`source apple_health/bin/activate`

Install dependencies

`pip3 install requirements.txt`

Parse the health data to CSV

`python3 parse_health.py <apple health data.xml>`

Start jupiter notebook

`jupyter notebook`
# Visualize Step Count on Calendar Heat Map

Visualize your Apple healthkit stepcounts as a calendar headmap. 

![Step Count]('https://raw.githubusercontent.com/th3o6a1d/stepcount_heatmap/master/StepCount.png')

Citations: 

- https://github.com/markwk/qs_ledger/blob/master/apple_health/apple-health-data-parser.py for XML to CSV parser

- calmap python heatmap

## Usage

Export your apple health data. `mkdir data` and put exported xml data in folder.

Start virtual environment

`virtualenv apple_health`

`source apple_health/bin/activate`

Install dependencies. Will need the usual stuff plus calmap package.

`pip3 install requirements.txt`

Parse the health data to CSV using script borrrowed from above link.

`python3 parse_health.py <apple health data.xml>`

Start jupiter notebook

`jupyter notebook`
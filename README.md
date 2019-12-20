# health-insights
A big data project on building a public API with insights to a dataset for healthcare


## Getting Started

The project is broken down into 3 parts: 
* dataproc: All the health insights, database work, processing insights and the raw intelligence. 
* search-engine: The API work and the querying/search engine system
* web: the web server to render visualization and integrate dataproc and search-engine components

### Prerequisites

To run and setup the project you need python, node.js and NPM installed for the visualizations, which can be found [here](https://nodejs.org/en/). For the data processing you need python which can found [here](https://www.python.org/downloads/release/python-374/).

### Installing

To get started on visualizations:
```
git clone https://github.com/dsc-umass/health-insights.git

python3 setup.py
```
<!-- 
## Deployment

To get started on visualizations:
```
cd dataproc/

sudo pm2 start api.py --name health-insights --interpreter=python3 -->

## Built With

* [GCP Dataproc](https://cloud.google.com/dataproc/) - Spark and Hadoop on the Cloud
* [Flask](http://flask.palletsprojects.com/en/1.1.x/) - API Framework
* [PM2](https://pm2.keymetrics.io/) - Production Server and Load Balancing


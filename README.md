# automation-report

Scrape Jenkins cucumber report and create XLSX report.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
python 3.5+
python 3-venv
Must be connected to VPN
no myenv folder on first run
```

### Usage

```sh
$python3 ccp_daily_automation.py [-h] [-s | -r | -t]
optional arguments:
         -h, --help        show this help message and exit
         -s, --smoke       Generate Smoke Report
         -r, --regression  Generate Regression Report
         -t, --test        Test mode, Smoke Confirmation only
```

## Built With

* Python3
* OpenPyXL
* Requests

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Russell Delogu** - *Initial work*
* **Francis Lagadia** - *XLSX output*

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc

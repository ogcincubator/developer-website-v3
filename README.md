# OGC Developer Website

## Introduction
This repository hosts the source of the OGC Developer Website https://developer.ogc.org

Currently, the website is served from the [gh-pages](https://github.com/opengeospatial/developer-website/tree/gh-pages) branch.

## Version 3.0
This is now the main version.

Install:

`npm install`

Run locally (includes development server):

`npm start`

Commit all your changes to the `master` branch. **The `gh-pages` branch will be wiped each time, and generated dynamically from [GitHub actions](https://github.com/ogcincubator/developer-website-v3/actions/)**. Apart from copying the static build, the action will copy the `api` folder and pull remote repos that live under `developer.ogc.org`. If you need to add anything else, just edit the [workflow file](https://github.com/ogcincubator/developer-website-v3/blob/master/.github/workflows/main.yml) directly.


## Intellectual Property Rights

The content of this repository is copyrighted by the Open Geospatial Consortium (OGC) and may be [licensed](https://github.com/opengeospatial/er_template/blob/master/LICENSE) for designated purposes.

Attention is drawn to the possibility that some of the elements of this document may be the subject of patent rights. The Open Geospatial Consortium shall not be held responsible for identifying any or all such patent rights.

Recipients of this document are requested to submit, with their comments, notification of any relevant patent claims or other intellectual property rights of which they may be aware that might be infringed by any implementation of the standard set forth in this document, and to provide supporting documentation.
# OGC Developer Website

## Introduction
This repository hosts the source of the OGC Developer Website https://developer.ogc.org

Currently, the website is served from the [gh-pages](https://github.com/opengeospatial/developer-website/tree/gh-pages) branch. Read [this note](#note-about-publishing-the-website), to understand how the website is generated. 

## Version 3.0
This is now the main version.

Install:

`npm install`

Run locally (includes development server):

`npm start`

### Note about Publishing the Website

Commit all your changes to the `master` branch. **The `gh-pages` branch will be wiped each time, and generated dynamically from [GitHub actions](https://github.com/ogcincubator/developer-website-v3/actions/)**. Apart from copying the static build, the action will copy the `api` folder and pull remote repos that live under `developer.ogc.org`. If you need to add anything else, just edit the [workflow file](https://github.com/ogcincubator/developer-website-v3/blob/master/.github/workflows/main.yml) directly.

## Contributing 🤝

This website is a live project and we welcome contributions from the community! If you have suggestions for improvements, found a bug, or want to add new features, feel free to:

* Open an [issue](https://github.com/opengeospatial/ogc-records-website/issues) to start a discussion
* Submit a [pull request](https://github.com/opengeospatial/ogc-records-website/pulls) with your proposed changes

We appreciate your support in making this website better!

## Intellectual Property Rights

The content of this repository is copyrighted by the Open Geospatial Consortium (OGC) and may be [licensed](https://github.com/opengeospatial/er_template/blob/master/LICENSE) for designated purposes.

Attention is drawn to the possibility that some of the elements of this document may be the subject of patent rights. The Open Geospatial Consortium shall not be held responsible for identifying any or all such patent rights.

Recipients of this document are requested to submit, with their comments, notification of any relevant patent claims or other intellectual property rights of which they may be aware that might be infringed by any implementation of the standard set forth in this document, and to provide supporting documentation.
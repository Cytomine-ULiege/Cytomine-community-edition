# Cytomine ULiège Community Edition

[![](https://img.shields.io/github/v/release/Cytomine-ULiege/Cytomine-community-edition)](https://github.com/Cytomine-ULiege/Cytomine-community-edition)
[![](https://img.shields.io/docker/pulls/cytomine/installer)](https://hub.docker.com/r/cytomine/installer/)

Cytomine Community Edition is the open source edition of the Cytomine software.

This repository provides the new way to install Cytomine Community Edition, based on Docker compose.

## DISCLAIMERS
* This version opens a new way to manage data within Cytomine. It is recommended for new projects starting from scratch, but NOT TO UPGRADE projects already running any Legacy edition of Cytomine (version 2 or 3). Please contact us if you have such needs.
* This version do not include any AI engine for the moment. This will be added in next release. So if you need to run AI within your Cytomine, please consider the last release of the [Legacy edition of Cytomine](https://github.com/Cytomine-ULiege/Cytomine-bootstrap).

## Install

Follow the installation procedure described here:
https://doc.uliege.cytomine.org/admin-guide/ce/ce-install

## In all cases

The password of the `admin` account is available in the cytomine.yml file : `cat cytomine.yml | grep ADMIN_PASSWORD:`

To learn how to use Cytomine please refer to the [user guide in our documentation](https://doc.uliege.cytomine.org/user-guide/).

Note: All Cytomine data is now stored in docker volumes (Postgres, Mongo, images and download buffers) and no more in folders.

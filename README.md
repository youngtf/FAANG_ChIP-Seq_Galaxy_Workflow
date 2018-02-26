Galaxy Tools for ChIP-Seq data analysis (FAANG standard)
========================================================

This repo includes a set of Galaxy tools that can be used to analyze Chip-seq data in [Galaxy](https://galaxyproject.org/) servers.

Currently the repo includes three parts: 

1. Custom Galaxy tools (scripts and corresponding .xml files) that can be used in Galaxy servers (administrator permission needed).
2. Workflow files for main Galaxy server.
3. Workflow files for local Galaxy server.

More details about the three parts can be found in the description in the three folders.

## Available Galaxy Servers

A full description of available Galaxy choices can be found [here](https://galaxyproject.org/choices/).

The tools in this repo are tested in the main server and local instances (including [this Docker image](https://github.com/bgruening/docker-galaxy-stable)). Galaxy on the Cloud has not been tested for the tools.

### Public Galaxy Server

The [main Galaxy server](https://usegalaxy.org) provides a free solution to run Galaxy workflows. It is very well maintained and has strong technical support. Most famous tools are ready for use.  

However, custom tools (such as those in this repo) can not be used in the main Galaxy server. 

### Local Galaxy instance 

A detailed manual to install a local Galaxy instance is [here](https://galaxyproject.org/admin/get-galaxy/)

### Docker image (Recommended)

It is recommended to use [this Docker image](https://github.com/bgruening/docker-galaxy-stable) for running Galaxy locally. [Docker](https://www.docker.com/) provides a more friendly graphic user interface to start a server, and the Galaxy Docker Image is a clean, independent, ready-to-use Galaxy environment. More documentation of them can be found in their pages, and a manual specific for our tools is also in preparation.


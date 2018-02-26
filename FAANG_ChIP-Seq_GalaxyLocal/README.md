Galaxy Tools for ChIP-Seq data analysis (FAANG standard)
========================================================

## Galaxy workflow for local Galaxy instance

This folder includes workflow files designed to be used in local Galaxy instance (including Docker images). __Applying the workflow may require an administrator account in the local Galaxy instance, as some tools in the workflow need to be install through Tool Shed or even manually__.

## Features

Currently the workflow can finish the following analysis:

1. Raw reads trimming, QC, alignment.
2. ChIP-seq peak calling

When tools are ready for quality reports (e.g. for alignment, ChIP-Seq or peak calling), corresponding workflow will be updated here.

## Usage

A munual is in preparation.

## Known issues
1. When MACS2 is also installed in the system through other package management tools (e.g. pip), the MACS2 tools in the Galaxy may failed to start. Removing the MACS2 installed through other package management tools may solve the problem. Using Docker image may help to avoid the problem as it is more independent.

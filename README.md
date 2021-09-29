# EDDE Hello World Deployment

[![CircleCI](https://circleci.com/gh/greyshore/edde-helloworld-deployment/tree/main.svg?style=svg&circle-token=ceb450715a433895e01c88d75f647af5b8480119)](https://circleci.com/gh/greyshore/edde-helloworld-deployment/tree/main)

https://steddestaticweb.z13.web.core.windows.net/

Repository with a basic application to be deployed using the included CircleCI 
pipeline configuration.

## Project Structure

A single `index.html` file to be uploaded to cloud storage and be served to test
the pipeline capability.

Circle CI pipeline configuration at `.circleci/config.yml` which will take the
files in this repository and uploaded them to a cloud storage repository to be
served to the internet.

## How To Install

As of now this project requires no setup. The necessary steps to deploy are
defined in the pipeline configuration file located in `.circleci/config.yml`.

The pipeline is defined at 
https://app.circleci.com/insights/github/greyshore/edde-helloworld-deployment

## Usage

Simply modify the `index.html` file and push the code to see your changes
reflected. Also, modify the `.circleci/config.yml` file to change the pipeline

## Public Website URL

You can visit the website generated here:

https://steddestaticweb.z13.web.core.windows.net/

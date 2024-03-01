# Google Cloud Platform (GCP) - ELT Serverless Event Driven Infra As Code Template

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit) [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) [![Coverage Status](https://coveralls.io/repos/github/joemccann/dillinger/badge.svg?branch=master)](https://coveralls.io/github/joemccann/dillinger?branch=master)


# Summary of the project

A Google Cloud Platform (GCP) - ELT Serverless Event Driven Infra As Code Template with multiple environments using Terraform and Terragrunt.



## Table of Contents

* [Overview](#overview)
* [Stack](#stack)
* [Getting Started](#getting-started)
* [Installation](#installation)
* [License](#license)




## Overview

This template to be used to instanciate a new ELT project on GCP.

3 Modules Extract, Load and Transform will be created.

Each module (Extract, Load and Transform) will have its own domains.

Each domain will have its own sources


work in progress...

#### Ressouces:

It will create the following resources:

* Cloud Scheduler
* Cloud Tasks
* Cloud Event Arch
* Cloud Pub/Sub
* Cloud Run
* Cloud Functions - Python
* Cloud Storage
* Cloud BigQuery

#### Infrastructure as code (IAC):

* Terraform
* Terragrunt

### Environments:

Will create 3 seperate environments:

##### Non production environments:

* DEV
* STAGE

##### Production environment:

* PROD

####  Architecture

Simplified architecture:

![Architecture simplified](./docs/images/architecture.png)


## Stack

#### Services used:

* Google cloud platform (GCP)

* Google cloud Scheduler

* Google cloud Tasks

* Google cloud Event Arch

* Google cloud Pub/Sub

* Google cloud Run

* Google cloud Functions - Python

* Google cloud Storage

* Google cloud BigQuery

####  Tooling Infrastructure as code (IAC)

* Terraform

* Terragrunt


## Getting Started

### Prerequisites

* Terraform    https://www.terraform.io/downloads.html

* Terragrunt    https://terragrunt.gruntwork.io/docs/getting-started/install

* GCP account   https://cloud.google.com/

* Python 3.11.0  https://www.python.org/downloads/release/python-3110/


* Google Cloud CLI   https://cloud.google.com/sdk/docs/install




### Installation

######Todo


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

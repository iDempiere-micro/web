# iDempiere micro - highly modularized Java + Kotlin OSGi and Spring back-ends compatible with iDempiere

[![CircleCI](https://circleci.com/gh/iDempiere-micro/idempiere-micro-spring/tree/master.svg?style=svg)](https://circleci.com/gh/iDempiere-micro/idempiere-micro-spring/tree/master)
[![Maintainability](https://api.codeclimate.com/v1/badges/279819f3dc54d47b941c/maintainability)](https://codeclimate.com/github/iDempiere-micro/idempiere-micro-spring/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/279819f3dc54d47b941c/test_coverage)](https://codeclimate.com/github/iDempiere-micro/idempiere-micro-spring/test_coverage)

When building a new business system there is a lot of stuff you can reuse. Most of the well-known libraries give you reuse on the technological level: logging, users, access control etc.

We decided to raise the bar a little bit higher and give software developers a possibility to reuse business entities from one of the most advanced open source Enterprise Resource Planning (ERP) software - [iDempiere](http://www.idempiere.org/).

So instead of building everything from scratch you simply:

- **choose the iDempiere modules** you need and include them in your Java or Kotlin OSGi code (you can start with our [empty Scaffold project](https://github.com/iDempiere-micro/Scaffold)) OR use the **complete Spring backend** (see the [source code of the iDempiere-micro Spring backend](https://github.com/iDempiere-micro/idempiere-micro-spring)).
- enhance the database with your **custom tables and views**
- **extend the standard iDempiere code** if needed
- use the resulting application as a **REST server** with builtin authentication, users & roles etc., all the functionality from iDempiere modules included plus your custom code

[Read the documentation.](https://github.com/iDempiere-micro/Docs) [Clone the contributor's repository.](https://github.com/iDempiere-micro/idempiere-micro)

## Quick start for testing iDempiere micro OSGi using Docker

1. install [Docker](https://docs.docker.com/install/)
2. follow the steps in [the Docker image for iDempiere Micro on Karaf repository](https://github.com/iDempiere-micro/idempiere-micro-docker#quick-start)

## Quick start for testing staging od [iDempiere micro using Spring version](https://github.com/iDempiere-micro/idempiere-micro-spring) deployed to Dokku
1. `wget http://idempiere-micro-spring.staging.hsharp.software//user/GardenUser/login/GardenUser`

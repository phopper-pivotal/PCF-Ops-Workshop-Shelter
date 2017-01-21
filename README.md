# Pivotal Cloud Foundry Operations Workshop
This workshop will focus on the PCF Operator persona. We will review details about Pivotal Cloud Foundry architecture, operations (including installation), metrics and logging.

## Goal of Workshop
- Application and platform are operational, provisioned, and up to date for millions of users
- High availability and scaling to meet user needs
- Platform security 
- Reducing administrative overhead
- Ability to install, maintain, and troubleshoot an instance (or instances) of PCF

## Outcomes of Workshop
- PCF installation and upgrades (using BOSH)
- Provisioning services and using service broker/creating tiles for devs
- Configuring and using PCF ops manager
- Understanding and using PCF monitoring capabilities (logging, metrics, firehose)
- Scaling an application using PCF
- Scale the platform
- Understanding of PCF Elastic Runtime

## Agenda
# note here, let's link in the slides instead of later (in course materials)
Time | Session
---- | -------
8:00 AM - 8:15 AM | _Introduction by Shelter Insurance_
8:15 AM - 9:00 AM | _Session 1: Some Title_
9:00 AM - 10:00 AM | _Session 2: Some Title_
10:00 AM - 11:00 AM | _Session 3: Some Title_
11:00 AM - 12:00 AM | _Session 4: Some Title_

This is a _loose_ schedule for the day. We will adjust as necessary based on our pace through the material.

The lectures for this workshop are generally light and are only intended to set the stage for the hands-on labs.
The overwhelming majority of our time will be spent engaging with the technology directly!

## Getting Started

### Pre-requisites
Start by downloading and installing the appropriate prerequisite tools.
- [Cloud Foundry CLI](https://goo.gl/M0pH4i) to interact with a cloud foundry instance
- [Apache Maven](http://info.pivotal.io/HI002010A6ZlRJR1NeU00eC) to build labs using Maven
- [Gradle](https://services.gradle.org/distributions/gradle-3.1-all.zip) to build labs using Gradle
- [Git Client](https://git-scm.com/downloads) to clone Github repo or download and unzip
- An IDE, like [Spring Tool Suite](https://spring.io/tools/sts/all) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [Java SE Development Kit](http://info.pivotal.io/n0I60i3021AN0JU0le10CRR)

### Download Materials
Next, download the course materials. This can be accomplished either through the GitHub website by downloading a repository zip and unzipping locally, or if you have Git installed, use the following commands:
```
$ git clone https://github.com/phopper-pivotal/PCF-Dev-Workshop-Shelter.git
$ cd PCF-Dev-Workshop-Shelter/
```

### PCF Environments
Finally, in order to perform the labs, you must be connected or logged into a live PCF environment. Initially you were asked to create a Pivotal Web Services (PWS) account for use in labs and afterwards. Two other environments have also been made available for use. Please see the [Pivotal Cloud Foundry Environment document](Common/env_info.md) for details. You should have been assigned a student number and PCF instance at registration. Otherwise the instructors will provide that information for your use.

## Instructors
- Chris Busch, Pivotal Platform Architect, cbusch@pivotal.io
- Jenny McLaughlin, Pivotal Platform Architect, jmclaughlin@pivotal.io
# [User Guide](https://henryssondaniel.github.io/teacup.github.io/)
[![Build Status](https://travis-ci.com/HenryssonDaniel/teacup-java-engine-testng.svg?branch=master)](https://travis-ci.com/HenryssonDaniel/teacup-java-engine-testng)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=HenryssonDaniel_teacup-java-engine-testng&metric=coverage)](https://sonarcloud.io/dashboard?id=HenryssonDaniel_teacup-java-engine-testng)
[![latest release](https://img.shields.io/badge/release%20notes-1.0.0-yellow.svg)](https://github.com/HenryssonDaniel/teacup-java-engine-testng/blob/master/doc/release-notes/official.md)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.henryssondaniel.teacup.engine/testng.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22io.github.henryssondaniel.teacup.engine%22%20AND%20a%3A%22testng%22)
[![Javadocs](https://www.javadoc.io/badge/io.github.henryssondaniel.teacup.engine/testng.svg)](https://www.javadoc.io/doc/io.github.henryssondaniel.teacup.engine/testng)
## What ##
Custom TestNG engine.  
This engine interacts with the Teacup core project to get fixture data, such as the current fixture
and added clients/servers.
## Why ##
It can be time and resource consuming to use fixtures.  
Therefore this engine will change the order of the tests before executing them so that the minimal
fixture changes are required.
## How ##
This is done by extending the TestNG engine.
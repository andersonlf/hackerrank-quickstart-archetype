hackerrank-quickstart-archetype
===============================

[![Build Status](https://travis-ci.org/andersonlfeitosa/hackerrank-quickstart-archetype.svg?branch=master)](https://travis-ci.org/andersonlfeitosa/hackerrank-quickstart-archetype)


Summary
-------
The project is a Maven archetype for challenge programming projects of HackerRank.

Installation
------------

To install the archetype in your local repository execute following commands:

```bash
    git clone https://github.com/andersonlfeitosa/hackerrank-quickstart-archetype.git
    cd hackerrank-quickstart-archetype
    mvn clean install
```

Create a project
----------------

To generate project for a challenge programming execute following command:

```bash
    mvn archetype:generate \
        -DinteractiveMode=false \
        -DarchetypeGroupId=hackerrank \
        -DarchetypeArtifactId=quickstart \
        -DarchetypeVersion=1.0.0-SNAPSHOT \
        -DarchetypeRepository=nexus \
        -DgroupId=my.groupid \
        -DartifactId=my-artifactId \
        -Dversion=version
```


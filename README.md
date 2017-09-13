# Parent Maven POM

The [parent Maven POM](https://jonasrutishauser.github.io/parent/snapshot) for my github projects.

[![GNU Lesser General Public License, Version 3, 29 June 2007](https://img.shields.io/github/license/jonasrutishauser/parent.svg?label=License)](http://www.gnu.org/licenses/lgpl-3.0.txt)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.jonasrutishauser/parent.svg?label=Maven%20Central)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.jonasrutishauser%22%20a%3A%22parent%22)
[![Build Status](https://img.shields.io/travis/jonasrutishauser/parent/master.svg?label=Build)](https://travis-ci.org/jonasrutishauser/parent)

## Releasing

* Execute `mvn -B release:clean release:prepare release:perform`
* Deploy site `(cd target/checkout; mvn -P release site-deploy)`

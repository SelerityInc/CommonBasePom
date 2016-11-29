# CommonBasePom

Common parent POMs for Selerity Java projects.

* [Available POMs](#available-poms)
* [Questions/Support](#questionssupport)

[![Build Status](https://travis-ci.org/SelerityInc/CommonBasePom.svg?branch=master)](https://travis-ci.org/SelerityInc/CommonBasePom)

## Available POMs

For libraries, `LibraryBasePom` is a good default choice.

For applications, `ApplicationBasePom` is a good default choice.

The following POMs are available:

* `CommonBasePom`: Parent of all POMs. You should not use this one directly, but use one of the type specific POMs instead. Provides basic infrastructure from dependency versioning, git commit extraction up to release profiles.
* `LibraryBasePom`: Base POM for libraries. Enables plugins needed for libraries and adds some commonly library dependencies.
* `ApplicationBasePom`: Base POM for applications. Enables plugins needed for applications, adds some commonly library dependencies, and manages meta data like setting the jar's main class and corresponding build properties.

## Questions/Support

If you run into issues or have questions, please let us know at support@seleritycorp.com

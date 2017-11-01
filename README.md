# CommonBasePom

Common parent POMs for Selerity Java projects.

* [Available POMs](#available-poms)
* [Questions/Support](#questionssupport)

[![Build Status](https://travis-ci.org/SelerityInc/CommonBasePom.svg?branch=master)](https://travis-ci.org/SelerityInc/CommonBasePom)

## Available POMs

For libraries, `LibraryBasePom` is a good default choice.

For applications, `ApplicationBasePom` is a good default choice.

The following POMs are available:

* `CommonBasePom`: Parent of all POMs. Use this POM only, if you want to bring version and dependency information into legacy projects without enforcing formatting etc. Otherwise, you should not use this one directly, but use one of the type specific POMs instead. Provides dependency versioning, and plugin configuration, but does not use plugins that enforce formatting, styles, or resources.
* `StandardBasePom`: Extends `CommonBasePom` by adding plugins that enforce formatting, enforce resources, and extract more information (E.g.: git commit).
* `LibraryBasePom`: Base POM for libraries. Enables plugins needed for libraries and adds some commonly library dependencies.
* `ApplicationBasePom`: Base POM for applications. Enables plugins needed for applications, adds some commonly library dependencies, and manages meta data like setting the jar's main class and corresponding build properties.

## Questions/Support

If you run into issues or have questions, please let us know at support@seleritycorp.com

# Introduction

This modules disable Studio snapshot validation, waiting for it to be optimized (see [NXP-25732](https://jira.nuxeo.com/browse/NXP-25732)).

If the Studio module is not aligned with the current server target platform, or is declaring dependencies that are not available on the server, user will not be warned anymore.

This module also includes a patch of the HotReloadStudioSnapshot Nuxeo operation, as it was not taking into account the property to properly disable validation.


# Licensing

[GNU Lesser General Public License (LGPL) v2.1](http://www.gnu.org/licenses/lgpl-2.1.html)

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with
SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris.
More information is available at [www.nuxeo.com](http://www.nuxeo.com).

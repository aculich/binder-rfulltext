# binder-rfulltext
example using MRAN timemachine snapshot to access CRAN fulltext package

[Package ‘fulltext’](https://cran.r-project.org/web/packages/fulltext/index.html)
was removed from the CRAN repository and archived on 2021-11-22 for policy violation.

Formerly available versions can be obtained from the [archive](https://cran.r-project.org/src/contrib/Archive/fulltext).

It can also be accessed through the Timemachine on [MRAN](https://mran.microsoft.com/).

This repo demonstrates how to use [Binder](https://mybinder.org/) with MRAN snapshots to access the archived version for the purposes of reproducibility. We do this by [specifying an R environment with a runtime.txt file](https://mybinder.readthedocs.io/en/latest/examples/sample_repos.html?highlight=sample#specifying-an-r-environment-with-a-runtime-txt-file)

Using the latest [R version 4.0.2](https://cran.r-project.org/src/base/R-4) released on 2021-11-01 with the last MRAN Timemachine daily snapshot of [fulltext from 2021-11-22](https://mran.microsoft.com/package/fulltext).

## Try it out!
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aculich/binder-rfulltext/HEAD)

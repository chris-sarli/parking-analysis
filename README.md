# Downtown Providence Parking Analysis

This repository holds files for calculations of the insane amount of parking in Downtown Providence, RI.

Currently, all calculations are done in [`notebooks/make.ipynb`](notebooks/make.ipynb), and collected in
[`outputs.md`](outputs.md).

`make.ipynb` also creates an HTML file collecting all of this information in a public-facing format. This file is generated at `docs/index.html`, so that <a href="https://chris-sarli.github.io/parking-analysis/">it can be hosted on GitHub Pages</a>.

[`notebooks/To-Do.ipynb`](notebooks/To-Do.ipynb) is used to keep track of data which is not yet considered complete.

The `licenses` directory is a scratch area used to comb through some data from the Board of Licenses, searching for capacity data.

If you'd like to work on these files, you will need to use [Conda](https://conda.io/en/latest/). The environment can be
recreated from [`environment.yml`](environment.yml).

Data is retrieved from [OpenStreetMap](https://www.openstreetmap.org/) using [OSMnx](https://github.com/gboeing/osmnx).

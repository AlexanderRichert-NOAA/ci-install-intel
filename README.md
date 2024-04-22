# install-intel

This repository provides a GitHub Action for download and caching the Intel
Classic and oneAPI compilers for Linux

This repository supports [NCEPLIBS](https://github.com/NOAA-EMC/NCEPLIBS) CI
workflows.

To submit bug reports, feature requests, or other code-related issues including
usage questions, please create a [GitHub
issue](https://github.com/NOAA-EMC/build-nceplibs/issues). For general
NCEPLIBS inquiries, contact [Ed Hartnett](mailto:edward.hartnett@noaa.gov)
(secondary point of contact [Alex Richert](mailto:alexander.richert@noaa.gov)).

### Authors

[Alex Richert](mailto:alexander.richert@noaa.gov)

### Usage

To use this Action, include the following step in your GitHub Actions workflow:
```
      - name: "Install Intel compilers"
        uses: NOAA-EMC/install-intel@develop
        with:
          install-mpi: true
          env-update: true
```

See `actions.yml` for the full list of available options and their defaults.

## Disclaimer

The United States Department of Commerce (DOC) GitHub project code is provided
on an "as is" basis and the user assumes responsibility for its use. DOC has
relinquished control of the information and no longer has responsibility to
protect the integrity, confidentiality, or availability of the information. Any
claims against the Department of Commerce stemming from the use of its GitHub
project will be governed by all applicable Federal law. Any reference to
specific commercial products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their endorsement,
recommendation or favoring by the Department of Commerce. The Department of
Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used
in any manner to imply endorsement of any commercial product or activity by DOC
or the United States Government.

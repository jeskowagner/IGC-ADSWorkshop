# File taken from https://github.com/espm-157/devcontainers-rstudio/
FROM ghcr.io/rocker-org/devcontainer/geospatial:4.2

## Install additional deps like this:
RUN R -q -e 'renv::install(c("tidymodels", "skimr", "GGally", "caret", "corrr"))'

## Or like this:
# RUN R -e 'remotes::install_deps()'

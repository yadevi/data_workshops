FROM rocker/verse:4.0.0

RUN apt-get update \
  && apt-get install -y --no-install-recommends \
    byobu \
  && apt-get clean \
  && install2.r --error \
    conflicted \
    cowplot \
    knitr \
    revealjs \
    snakecase

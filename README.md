Integrating geographic analysis in transport planning workflows: a
review of open source options
================
Robin Lovelace
2019-05-09

``` r
# get citations
refs = RefManageR::ReadZotero(group = "418217", .params = list(collection = "JFR868KJ", limit = 100))
RefManageR::WriteBib(refs, "software.bib")
```

    ## Writing 64 Bibtex entries ... OK
    ## Results written to file 'software.bib'

## Abstract

Software for working with geographic data has long been used in
transport planning. Transport planning workflows have tended to separate
the main data analysis stages from vital geographic processing and map
making stages. Data preprocessing and analysis stages are generally done
in dedicated transport planning and spreadsheet software. Geographic
analysis and cartographic visualisation stages are generally done in a
dedicated ‘geographic information system’ (GIS). This paper explores how
this situation has arisen due to historical specialisation and
monopolisation of transport planning software, based on existing
literature, before outlining an integrated approach that combines data
analysis and geographic processing stages in a single workflow. Three
software ecosystems (QGIS, Python and R) are reviewed in detail;
alternative current and potential future approaches, including ‘cloud
lock in’ are discussed; and the relative merits of different approaches
are discussed. Building on this discussion, I argue that integrating
data analysis and geographic processing in a single analysis has major
advantages and outlines concrete steps that researchers, public sector
transport planners, and transport planning analysts and consultants can
use. The paper concludes that ‘integrated approach’ can support
efficient, scalable and reproducible transport planning workflows which
can provide a strong and transparent evidence base needed for rapid
transition away from fossil fuels in the transport sector.

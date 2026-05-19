# eAnalytics 0.3.1

## New Features

* Electric and Oil industry tabs now include a **Performance** tab with histogram and heatmap visualizations.
* Electric and Oil industry tabs now include an **Explorer** tab with a GoogleVis motion chart for tracking trends over time.
* Added a company filter to the Trends tab for Electric, Gas, and Oil industries.
* Added a "Companies by Industry" bar chart to the home page dashboard.

## Minor Improvements and Bug Fixes

* Updated industry menu icons (Electric → bolt, Hydropower → tint, Natural Gas → fire, Oil → flask).
* Refreshed underlying `energyr` data.
* Updated author contact email in DESCRIPTION.
* Updated `RoxygenNote` to 7.3.3.

## Infrastructure

* Added `R-CMD-check.yaml` for matrix CI testing across macOS, Windows, and Ubuntu (release/devel/oldrel-1).
* Added `pkgcheck.yaml` for rOpenSci automated package checks.
* Upgraded `pkgdown.yaml` actions to current versions.
* Removed obsolete `r.yml` workflow.
* Added `shinytest2` and `testthat (>= 3.0.0)` to `Suggests` in DESCRIPTION.

# eAnalytics 0.3

## Minor improvements and bug fixes

* `eAnalytics()` now has the same UI locally as on shinyapps.io.

# eAnalytics 0.1.4

## Major Changes

* Added tests 

## Minor Changes

* Added orcid

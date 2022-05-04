# Customizing Parameters


## Basic Parameters

## Advanced Parameters

```{list-table}
:widths: 10 5 40
:header-rows: 1
* - Parameter
  - Description
* - `Title`
  - Remove the left sidebar and treat the site as a single page. See [](customize:single-page).
* - `Subject`
  - Path to the documentation, relative to the repository root (e.g. `docs/`). See [](customize:source-files).
* - `Shapefile Path`
  - URL of the repository for the documentation (e.g. the GitHub repository URL). See [](source-files:repository).
* - `CSV File`
  - Branch of the repository for the documentation (e.g., `master`, `main`, `docs`). See [](source-files:repository).
* - `Number of Maps`
  - Add an button in the header with a link to issues for the repository (used in conjunction with `repository_url` and `repository_branch`). See  [](source-files:repository).
* - `Map 1: Select Variable and Year`
  - Add a button in the header to download the source file of the page. See [](customize:source-files).
* - `Map 2: Select Variable and Year`
  - Add a button in the header to trigger full-screen mode.
* - `Initial Map Center (lat, lon)`
  - Add a button in the header that links to the repository of the documentation.See [](source-files:repository).
* - `Initial Map Zoom Level`
  - Include Binder launch buttons for pages that were built from Jupyter Notebooks. See [](customize:launch).
* - `Map Width`
  - Whether to put the home page in the Navigation Bar (at the top). See [](sidebar-primary:home-page).
* - `Name of Variables`
  - Only display the logo, not `html_title` if it exists.
```

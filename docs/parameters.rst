Customizing Parameters
==================================================================

=======================
Basic Parameters
=======================
.. image:: images/cybergisx4.png
  :width: 800
  :alt: basic_parameter
  :target: parameters.html

Fill out text here.

=======================
Advanced Parameters
=======================

.. list-table::
  :widths: 10 40
  :header-rows: 1

  * - Parameter
    - Description
  * - ``Title``
    - Title text that would appear in the top of the result visualization file.
  * - ``Subject``
    -
  * - ``Shapefile Path``
    - File path of shapefile that would be a base map layer to map visualization.
  * - ``CSV File``
    - File path of the CSV file that you want to visualize on the maps.
  * - ``Number of Maps``
    - Number of maps to visualize in the HTML file.
  * - ``Map: Select Variable and Year``
    - Layers you want to visualize in the maps.
  * - ``Initial Map Center (lat, lon)``
    -
  * - ``Initial Map Zoom Level``
    -
  * - ``Map Width``
    -
  * - ``Name of Variables``
    - Write full name of variables to make variables names more intuitive.

.. image:: images/advanced.png
    :width: 600
    :alt: advanced_parameter
    :target: parameters.html

Below are chart-specific parameters, for MLC, CLC, and PCP respectively.

.. list-table::
  :widths: 10 40
  :header-rows: 1

  * - Parameter
    - Description
  * - ``Number of Chart(s)``
    - For MLC, number of MLC charts. For CLC and PCP, number of lines in a chart.
  * - ``Selected Variables``
    - Path to the documentation, relative to the repository root (e.g. `docs/`). See [](customize:source-files).
  * - ``Highlight Method``
    - This parameter only applies to MLC. Determine which time period to highlight, and in which color in 'start time, end time, colorcode' format (e.g., 2019, 2026, #fdff32).
  * - ``Top 10 Chart``
    - A Top 10 Chart linked with the right-side map.
  * - ``Exclude Outliers``
    - Exclude extreme outliers to avoid skewed results.

.. image:: images/advanced2.png
    :width: 600
    :alt: advanced_parameter
    :target: paramters.html

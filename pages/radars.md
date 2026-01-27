---
layout: radars # See _layouts/radars.html for page functionality
title: Radars
background:
  img: https://images.unsplash.com/photo-1625216109110-d444d70ff665?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2000&q=80
  by: Daniele Franchi
  href: https://unsplash.com/photos/g2fJ7d7eKSM
permalink: /radars/
toc: true # Works because _layout/radars.html is based on "default" and titles have ids
---

This list of radars in the Next Generation Weather Radar (NEXRAD) system is derived from a single [file maintained by NOAA](https://www.ncei.noaa.gov/access/homr/file/nexrad-stations.txt) for their [radar map](https://www.weather.gov/nl2/NEXRADView). Issues can be reported to [Alex Tedeschi](mailto:alexander.tedeschi@cornell.edu).

Metadata were last downloaded on 2026-01-25, processed using [this script](https://github.com/aloftdata/aloftdata.eu/blob/main/_data/OPERA_RADARS_DB.R) and resulted into [this JSON file](https://raw.githubusercontent.com/aloftdata/aloftdata.eu/main/_data/OPERA_RADARS_DB.json). Only radars with an ODIM code are shown. Status `0` indicates that the radar is no longer active. Note that [bird movement data](https://crow.aloftdata.eu/) is not available for all radars listed on this page.

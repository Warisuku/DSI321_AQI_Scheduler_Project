# DSI321_AQI_Scheduler_Project

#Thing Need to be edit before creating Docker Image
- `Dockerfile` (for creating Docker Image)
- `conjob.yaml` (for scheduler to work properly)
- `metadata.json` (for upload to CKAN)
- `scripy.py` (main code for doing scraping)

# Docker Image
Build Docker Image
```
Docker build -t warisk/weather_scripy:1.14 .
```

Push Docker Image
```
Docker push warisk/weather_scripy:1.14
```
# Project References
* https://www.iqair.com/th/air-pollution-data-api
* [Air Quality Index (AQI)](https://en.wikipedia.org/wiki/Air_quality_index)
* [API Reference](https://api-docs.iqair.com/)
* [Crontab Editor](https://crontab.guru/#*_*/6_*_*_*)
* [Weather Data Source](https://docs.google.com/spreadsheets/d/e/2PACX-1vQlEs3FxFPwm-dpvU1YdsfRgsbfT9WdiXJHZm9kJgGTziPnk-y3TWtftbSbxj6Fe_g0NxYgqyVHTVU5/pubhtml?gid=1397577608&amp;single=true&amp;widget=true&amp;headers=false)

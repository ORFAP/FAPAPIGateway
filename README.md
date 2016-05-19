# FAPAPIGateway

[![Build Status](https://travis-ci.org/ORFAP/FAPAPIGateway.svg?branch=master)](https://travis-ci.org/ORFAP/FAPAPIGateway)


##Starten

###IDE
1. Mit Intellij das Repo importieren

2. Lombok Plugin installieren und als Annotation Processors für das Projekt aktivieren (https://github.com/mplushnikov/lombok-intellij-plugin)

3. FapapiGatewayApplication.main als Spring Application starten

###Docker
```docker run -p 808X:8080 darenegade/fapapigateway```

##Api Gateway Mapping

* ```/**``` -> GUI
* ```/api/**``` -> Backend
* ```/crawler/**```-> Crawler



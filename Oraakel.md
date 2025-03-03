---
permalink: Oraakel
---

# Pääsuke Oraakel

The following specification is for systems that keep authorisations in Pääsuke and load them from there using X-Road queries.

* [Description of X-Road services provided by Pääsuke (Oraakliliides) - v1.0.0](https://e-gov.github.io/PH-Doku/files/x-road_services_provided_by_paasuke.v1.0.0.pdf)
* [OpenAPI definitions](https://app.swaggerhub.com/apis/TUGI/paasuke-oraakliliides/)

### X-road services in different X-road environments

The services are made available through X-road.

* [ee-dev](https://x-tee.ee/catalogue/ee-dev/GOV/70006317/volitused/): 
    * oraakel - Please note that this endpoint is connected to the development environment which might be unstable.
* [ee-test](https://x-tee.ee/catalogue/ee-test/GOV/70006317/volitused/): 
    * oraakel
    * oraakel-stage - connected with the pre-live environment at https://stage.eesti.ee/volitused that you can requst access (IP whitelisting)
* [EE](https://x-tee.ee/catalogue/EE/GOV/70006317/volitused/): 
    * oraakel (production system)

You need to fill in an [application](https://www.ria.ee/riigi-infosusteem/kesksed-platvormid-avalike-e-teenuste-pakkumiseks/paasuke)
to get access to the services.


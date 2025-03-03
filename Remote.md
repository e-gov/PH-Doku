---
permalink: Remote
---

# Remote authorisations

The following specification is for systems that keep authorisations on their own information system and open API to Pääsuke to query and change them

* [Description of X-Road services offered to Pääsuke - v1.0.5](https://e-gov.github.io/PH-Doku/files/xroad-services-offered-to-paasuke-v1.0.5.pdf)
* [OpenAPI definitions](https://app.swaggerhub.com/apis/TUGI/x-road-services-consumed-by-paasuke/)

### Sample provider application

There is a sample application that provides these X-road services. The application is built in Python and uses Postgres as a database.

* Sample provider application built in Python—[github.com/e-gov/PH-sample-provider-python](https://github.com/e-gov/PH-sample-provider-python) (based on 1.0.0)
* You can run it locally using Docker-compose
* The provider stores authorisations and persons in a Postgres database
* The application keeps state—so if you add an authorisation, then you can get it back


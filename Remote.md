---
permalink: Remote
---

# Kaugkinnitused

Järgnev spetsifikatsioon on mõeldud süsteemidele, mis hoiavad volitusi oma infosüsteemis ja avavad Pääsukele API päringute tegemiseks ja muutmiseks.


* [Pääsukesele pakutavate X-Road teenuste kirjeldus - v1.0.5](https://e-gov.github.io/PH-Doku/files/xroad-services-offered-to-paasuke-v1.0.5.pdf)
* [OpenAPI definitsioonid](https://app.swaggerhub.com/apis/TUGI/x-road-services-consumed-by-paasuke/)

### Näidisteenuse pakkuja taotlus

Nende X-tee teenuste pakkumiseks on olemas näidisrakendus. Rakendus on loodud Pythonis ja kasutab andmebaasina Postgresi.

* Pythonis ehitatud näidispakkuja rakendus – [github.com/e-gov/PH-sample-provider-python](https://github.com/e-gov/PH-sample-provider-python) (põhineb versioonil 1.0.0)
* Saate seda lokaalselt käivitada, kasutades Docker-compose'i
* Teenusepakkuja salvestab volitused ja isikud Postgresi andmebaasi.
* Rakendus säilitab oleku – seega kui lisate volituse, saate selle tagasi.



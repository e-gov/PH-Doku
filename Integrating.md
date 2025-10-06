---
permalink: Integrating
---


# Dokumentatsioon arendajale Pääsukesega liidestumiseks

## Peamised viisid Pääsukesega liidestumiseks:


1. Kõige levinum integratsioonimuster on see, et liidestuja hoiab volitusi Pääsukeses ja liidestuja pärib [Pääsukese pakutavaid](#specification-of-the-x-road-services-that-pääsuke-provides-to-other-parties) X-Road teenuseid .
2. Samuti on võimalik volitusi Pääsukeses hoida, kuid neile juurdepääsuks kasutada GovSSO teenust. Lisateavet saab [GovSSO dokumentatsioonist](https://e-gov.github.io/GOVSSO/Representee) .
3. Liidestuja hoiab volitusi oma infosüsteemis ja Pääsuke pärib liidestuja käest [Pääsukese pakutavaid](#specification-of-the-x-road-services-that-pääsuke-provides-to-other-parties) X-Road teenuseid X-tee teenuseid

## Pääsukese teistele osapooltele pakutavate X-tee teenuste spetsifikatsioon

[Oraakel](Oraakel) on teenuse, mis vastutab teistele osapooltele volituste kättetoimetamise eest.

## X-tee teenuste spetsifikatsioon, mida Pääsuke teistelt osapooltelt pärib

Kuidas liidestada [kaugsüsteeme](Remote) , mis hoiavad volitused enda poolel, aga muudavad need hallatavaks Pääsukese kasutajaliidese kaudu.
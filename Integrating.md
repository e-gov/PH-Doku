---
permalink: Integrating
---

# Documentation for the developer implementing the integration with Pääsuke

## Main ways to integrate with Pääsuke:
1. The most common integration pattern is that integrator keeps authorisations (in payloads referred to as mandates) in Pääsuke and the integrator queries X-Road services [offered by Pääsuke](#specification-of-the-x-road-services-that-pääsuke-provides-to-other-parties). 
2. It is also possible to keep authorisations in Pääsuke, but use GovSSO service to access the authorisations. More info can be found from [GovSSO documentation](https://e-gov.github.io/GOVSSO/Representee). 
3. integrator keeps authorisations on their information system and Pääsuke queries X-Road services [offered to Pääsuke](#specification-of-the-x-road-services-that-pääsuke-queries-from-other-parties) by the integrator

## Specification of the X-road services that Pääsuke provides to other parties

[Oraakel](Oraakel) is the name of the service responsible for serving authorisations other parties

## Specification of the X-road services that Pääsuke queries from other parties

How to integrate [remote](Remote) systems that keep authorisations on their side but make them manageable from the Pääsuke user interface.


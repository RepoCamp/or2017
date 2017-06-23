# or2017
Hydra in a box workshop for OR 2017


## Introductions
* Who are you?
* Where do you come from?
* What do you do?
* What do you want to learn?

## What is Hydra in a Box
* IMLS Grant with 3 partners, improve access to Samvera (formerly Hydra)
* Study the landscape, formulate use cases and personas. 
* Feature development on the Hyku application.
* One aspect is [HykuDirect](https://hykudirect.com/). Multi-tenant software as a service
  * In the AWS cloud
* Another aspect is "easy to install".

## What is Hyku
* A Samvera application based on the Hyrax library.
  * More about the relationship between Hyku ahd Hyrax:
    * [Hyku and Hyrax: How are they related and how are they different?](https://wiki.duraspace.org/pages/viewpage.action?pageId=85530575)
    * [Where do I start?](http://samvera.github.io/hyku-vs-hyrax.html)
  * [Full feature list](http://hyr.ax/about/#q3)
* Recipes for Docker (easy to install)
* Multi-tenanted (to support the HydraDirect service; not limited to AWS)
* Architectural components: Fedora, Solr, Redis, PostgreSQL, background workers
* Characterizing and transforming files: FITS, imagemagick, openoffice, ghostscript, ffmpeg

## What is Docker

Small containers that run services

> A container image is a lightweight, stand-alone, executable package of a piece of software that includes everything needed to run it: code, runtime, system tools, system libraries, settings. Available for both Linux and Windows based apps, containerized software will always run the same, regardless of the environment. Containers isolate software from its surroundings, for example differences between development and staging environments and help reduce conflicts between teams running different software on the same infrastructure. 


## What is docker-machine?
Docker running inside a VM (e.g. virtualbox), for older operating systems that don't natively support Docker.

## Getting started
* [Docker Installation Instructions](Install.md)
* [Hyku Installation Instructions](InstallHyku.md)
* [Hyku User Documentation](https://wiki.duraspace.org/display/hyku/User+Documentation)


[Continue to Tour](tour.md)

# Docker: DAMSREPO + Tomcat ( + Solr )

![Docker Build Status](https://img.shields.io/docker/build/ucsdlib/docker-tomcat-damsrepo.svg)

Because the current version of production DAMS requires a fairly specific set of
resources to function correctly, this image has been created that installs both
Solr and DAMSREPO into a Tomcat container, along with config files necessary.

Note this does not preload any data into either DAMSREPO or Solr, it is expected
that will happen in a `docker-compose.yml`, or a different post-build process.

# docker-matlabmcr2017a

[![Build Status](https://travis-ci.org/murphygroup/docker-matlabmcr2017a.svg?branch=master)](https://travis-ci.org/murphygroup/docker-matlabmcr2017a)
[![GitHub issues](https://img.shields.io/github/issues/murphygroup/docker-matlabmcr2017a.svg)](https://github.com/murphygroup/docker-matlabmcr2017a/issues)
[![GitHub forks](https://img.shields.io/github/forks/murphygroup/docker-matlabmcr2017a.svg)](https://github.com/murphygroup/docker-matlabmcr2017a/network)
[![GitHub stars](https://img.shields.io/github/stars/murphygroup/docker-matlabmcr2017a.svg)](https://github.com/murphygroup/docker-matlabmcr2017a/stargazers)
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://raw.githubusercontent.com/murphygroup/docker-matlabmcr2017a/master/LICENSE)

The [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html) is a standalone set of shared libraries that enables the execution of compiled MATLAB applications or components on computers that do not have MATLAB installed. When used together, MATLAB, MATLAB Compiler, and the MATLAB Runtime enable you to create and distribute numerical applications or software components quickly and securely.

To build an image using the `Dockerfile` in this repository, run the command

```
➜ docker build -t "murphylab/matlabmcr2017a" .
```

This should build an image

```
➜  docker container ls -a

CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS                        PORTS               NAMES
48dde52f2bc8        murphylab/matlabmcr2017a     "/bin/bash -c 'pyt..."   45 seconds ago      Exited (0) 39 seconds ago                         frosty_wescoff
```

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, [email](mailto:cellorganizer-dev@compbio.cmu.edu), or any other method with the owners of this repository before making a change.

---

Support for [CellOrganizer](http://cellorganizer.org/) has been provided by grants GM075205, GM090033 and GM103712 from the [National Institute of General Medical Sciences](http://www.nigms.nih.gov/), grants MCB1121919 and MCB1121793 from the [U.S. National Science Foundation](http://nsf.gov/), by a Forschungspreis from the [Alexander von Humboldt Foundation](http://www.humboldt-foundation.de/), and by the [Freiburg Institute for Advanced Studies](http://www.frias.uni-freiburg.de/lifenet?set_language=en).

[![MMBioS](https://i1.wp.com/www.cellorganizer.org/wp-content/uploads/2017/08/MMBioSlogo-e1503517857313.gif?h=60)](http://www.mmbios.org)

Copyright (c) 2007-2019 by the [Murphy Lab](http://murphylab.web.cmu.edu) at the [Computational Biology Department](http://www.cbd.cmu.edu) in [Carnegie Mellon University](http://www.cmu.edu)

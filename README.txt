# lwip MITM - A simple TCP/IP splitter

[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)

A simple but effective lightweight TCP/IP splitter (MITM) implementation, based on the LWIP TCP/IP stack from Adam Dunkels.

## Project description

The Slides/ folder contains the presentation of the project.
The Implementation/ folder contains the actual implementation of the mitm based on LWIP.
[Implementation/MITM/](Implementation/MITM/) folder contains the app, based on Socket API, for the mitm.
[Implementation/LWIP/](Implementation/LWIP/)folder contains the software of TCP/IP stack in two version, a slow, but stable one, and a fast, but unstable one.


## Development

To compile, use the makefile in [](MITM/main/)

*Works only on Unix BSD based systems.*
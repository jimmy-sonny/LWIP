# lwip MITM - A simple TCP/IP splitter

[![License](https://img.shields.io/badge/License-BSD%203--Clause-orange.svg)](https://opensource.org/licenses/BSD-3-Clause)

A simple but effective lightweight TCP/IP splitter (MITM) implementation, based on the LWIP TCP/IP stack from Adam Dunkels.

## Project Structure

[Slides/](Slides/) contains the keynote of the project.

[Implementation/](Implementation/) contains the actual implementation of the MITM.

[Implementation/MITM/](Implementation/MITM/) contains the code of the MITM support, based on the Socket API of lwip.

[Implementation/LWIP/](Implementation/LWIP/) contains the code of lwip TCP/IP stack in two versions, a slow, but stable one, and a fast, but unstable.


## Development

To compile, use the [Makefile](Implementation/MITM/main/Makefile)

*Works only on Unix BSD based systems.*
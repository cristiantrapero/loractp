# LoRaCTP: LoRa Content Transfer Protocol

This project allows to transfer blocks of bytes ("content") over a LoRa (pure LoRa, no LoRaWAN) channel. The library was tested with content of the size of up to 600kB.

Details of the protocol can be found in this paper:
> K. Nakamura, P. Manzoni, M. Zennaro, J. -C. Cano and C. T. Calafate, 
> "[Invited] LoRaCTP: a LoRa based Content Transfer Protocol for sustainable edge computing," 
> 2020 16th International Conference on Mobility, Sensing and Networking (MSN), 2020, pp. 539-545, 
> [doi: 10.1109/MSN50589.2020.00090.](https://doi.org/10.1109/MSN50589.2020.00090)


The repository is structured as follow:

- `src`: Contains the source code of the project concerning the implementation of the protocol.
- `tests`: Tests the source code through TDD methodology.
- `examples`: It contains some simple examples to run in Lopy4.
- `docs`: Documentation related to the development of the project and system directives.

## Hardware

All the code developed here have been tested in:
- **Lopy 4**: https://docs.pycom.io/datasheets/development/lopy4/
- **Pysense v1.0**: https://docs.pycom.io/datasheets/expansionboards/pysense/


## Firmware versions
Lopy 4 firmware version: **Pybytes 1.20.2.r6** released at 28-11-2021

Pysense v1.0 firmware version: **0.0.8**


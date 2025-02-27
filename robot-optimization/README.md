## First Architecture Instance: Optimal Hardware

In this folder, we store the code used for hardware optimization and the associated model (as referenced in the paper).

### Dependencies
- The parameterized dynamics are implemented in the open-source library [adam](https://github.com/ami-iit/adam). Please refer to its installation guidelines.
- For the results presented in the paper, we additionally exploit Coin [HSL linear solvers](https://licences.stfc.ac.uk/product/coin-hsl).
- Additional dependencies are listed in the `requirements.txt` and `deps.sh` files.

### Installation
To set up the full environment, you can use the provided Docker setup in this folder. Ensure you specify your own path for the HSL library during installation.


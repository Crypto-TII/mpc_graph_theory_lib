# mpc_graph_theory_lib (an`SCALE-MAMBA` implementation for Basic Graph Theory)

[![forthebadge](https://forthebadge.com/images/badges/built-by-codebabes.svg)](https://cryptography.tii.ae/about-us)\
This repository includes (currently we only recommend experimentation):

* Basic random sampling using `Dijkstra` with cubic complexity from Aly et al.
* Improved `Dijkstra` with cuadratic complexity from Aly and Cleemput.
* Will include complete test files.

## Pre-requisites
* `SCALE-MAMBA` 1.11 or above. 
* `numpy` 1.16 or above. (exclusively to __test__, which in this context means, execute [`test_graph_lib.mpc`](Programs/test_graph/test_graph.mpc)). You can also use []`FANNG-MPC`](https://github.com/Crypto-TII/FANNG-MPC).Just replace the existing library by this one and add the test file.

## Installation and Configuration
1. Download and configure `SCALE-MAMBA`:
2. Copy all  `.py` files __as is__ directly in the `Compiler` folder in `SCALE-MAMBA`. 
3. Copy the tests folders in the `Programs` folder of your `SCALE-MAMBA` installation. 
4. You can now run them and check all tests are in <span style='color:green'>green.</span> (NOT in <span style='color:red'>red.</span>)

## Contact Information:
If you have questions please contact any of the authors. Current repo maintainer is:\
Abdelrahaman ALY
  * [TII](mailto:abdelrahaman.aly@tii.ae) 
  * [Personal](mailto:abdelrahaman.aly@gmail.ae) 
 
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/abdito_8.svg?style=social&label=Follow%20%40abdito_8)](https://twitter.com/abdito_8)
## License
### Authors: 
* Abdelrahaman ALY


Copyright (c) 2022-2023 Technology Innovation Institute - Cryptography Research Centre.\
Licensed under the MIT license.


## rsa_acc_sage_implementation
SageMath Implementation comparing *hash to prime numbers* with *hash to large odd integers* and their impact on RSA-based dynamic accumulators and Wesolowski's proof of exponentiation protocol. 

### Requirements:
Before running the notebook, please install the following software/libraries:
- SageMath version >=9.5 (https://doc.sagemath.org/html/en/installation/index.html)
- PyCryptodome version>=3.19 (this should be installed in sage using pip. https://pypi.org/project/pycryptodome/)

### How to run the notebook:
1. Execute the first two cells to load the hardcoded primes that will be used to instantiate our RSA modulus and load the needed libraries
2. Execute the cell under **Utility functions** to load utility functions
3. Execute the 3 cells under **RSA Accumulator classes** to load RSA-based accumulator classes that use H_prime and H_odd, respectively.
4. Execute the cell under **Runing Test** to prepare the random entries that will be used for benchmarking
5. Set the value of *p_len, odd_len, hash_digest, prime_bit_length* based on the description given





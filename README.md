# Theory-of-Algorithms
## SHA256 Project:
This repository contains my attempt at writting SHA256 algorithm in C.

## Setup:
* Download a GCC compiler

* Clone this repository

## Running:
Navigate to location of download repository and run the following code:

	gcc -o sha256 sha256.c

Then run "./sha256 FileName.txt", Example using given test files:

	./sha256 Test.txt

## Testing:
In order to test my implementation of the sha256 algorithm I created 3 test files, first one contains "abc" the second contains "123" and the last one is empty.

**Correct Hash Outputs:**
Test = ba7816bf 8f01cfea 414140de 5dae2223 b00361a3 96177a9c b410ff61 f20015ad

Test2 = a665a459 20422f9d 417e4867 efdc4fb8 a04a1f3f ff1fa07e 998e86f7 f7a27ae3

Test3 = e3b0c442 98fc1c14 9afbf4c8 996fb924 27ae41e4 649b934c a495991b 7852b855

> **Note:** I got different results due to the fact that they are not to converted to little endian. The correct hash values above were gotten using an online SHA-256 hash calculator.

## Research
[SHA-256 Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)

## Authors
**Peter Larkin** 
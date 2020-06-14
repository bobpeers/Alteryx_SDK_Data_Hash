# Alteryx SDK Tool - Data Hash
Alteryx tool to hash an incoming data field


## Installation
Download the yxi file and double click to install in Alteyrx. The tool will be installed in the __Developer__ category.

![alt text](https://github.com/bobpeers/Alteryx_SDK_Data_Hash/blob/master/images/Alteryx_Category.png "Alteryx Developer Category")

## Usage
Takes the incoming data field and outputs a hash of the data using the selected hash, supports the following hashing algorithms.

* DSA
* DSA-SHA
* MD4
* MD5
* RIPEMD160
* SHA
* SHA1
* SHA224
* SHA256
* SHA384
* SHA512
* blake2b
* blake2s
* dsaEncryption
* dsaWithSHA
* ecdsa-with-SHA1
* sha3_224
* sha3_256
* sha3_384
* sha3_512
* whirlpool

## Outputs
Sucessful operations will be output to the O-Output, The hash will be appended to the incoming data.

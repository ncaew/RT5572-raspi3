RT5572
=========

Source code for RT5572 device


## USB ID are tested ok:
* 148f:5572

## On Ubuntu 16.04 64bit
* Native build is ok.
* STA Mode is failed.
* AP Mode do not test.

## On Raspberry Pi 3 kernel version: 4.4.50
* Native build is ok.
* STA Mode is passed.
* AP Mode is passed.

## Guild:
* Modify this file to match your case:
```./raspi/cross_compile.sh 
* And run ./raspi/cross_compile.sh 5572 arg1 arg2


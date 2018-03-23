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
* Cross build do not test.
* STA Mode is passed.
* AP Mode is passed.

## On Rock64
* Native build is ok. (maybe need build kernel for rock64 first)
* Cross build do not test.
* STA Mode do not test.
* AP Mode do not test.

## Guide:
* Modify this file to match your case:
```
./raspi/cross_compile.sh 
```
* And run:
```
./raspi/cross_compile.sh 5572 arg1 arg2
```

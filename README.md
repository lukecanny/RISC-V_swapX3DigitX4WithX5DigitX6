# swapX3DigitX4WithX5DigitX6

This repo contains the RISC-V assembly source code for Assignment 2 of EE451 System on Chip Design 1.

Developed by Anthony Bird and Luke Canny, October 2022.

This assembly program swaps the (X4)th bit of X3 with the (X6)th bit of X5.

## Register Summary

- x3, x5 			= 	source registers
- x4, x6 			= 	specifies digit position to swap for x3 & x5 respectively
- x7, x9 			= 	mask for x3 & x5 respectively
- x8, x10, x12 	= 	counters
- x11 			= 	holds difference between x4 & x6 values

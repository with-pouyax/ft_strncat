# ft_strncat

This repository features the implementation of the `ft_strncat` function, a custom version of the standard `strncat` function used in C programming for concatenating strings with a limit. This function appends the `src` string to the `dest` string up to `nb` characters, taking care to null-terminate the result.

## Overview

The `ft_strncat` function combines the functionality of string concatenation with the safety of limiting the number of characters to append, preventing buffer overruns. It includes a utility function `get_length` to calculate the length of a string, which aids in determining where to start appending `src` to `dest`.

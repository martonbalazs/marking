marking
===

I may collect some useful scripts here for calculating marks. The first one is

- hwdropper, a little Gawk script to help the "best x out of y" calculation. Run it as

```
hwdropper <file> <max points per HW> <how many to drop> <first column to look at> <last column to look at>
```

on a semicolon-separated .csv file; I believe it's clear what it does. The outcomes are added as the last three columns: total mark, percentage, and percentage rounded to integers.

I'm no programmer, so please don't blame me on the quality of the code. :-)
Licensed under GNU GPLv3.

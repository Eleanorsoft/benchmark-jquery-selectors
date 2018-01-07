# Benchmark: jQuery Selectors
This test compares speed of different jQuery selectors.

It runs 100 000 selections by name, by classname and by ID. And then it shows time spent.

The results are:
* the slowest selector is "By Name" (`input[name=input1]`)
* selector "By Class" (`.input1`) is faster by 45%-50% than "By Name"
* the fastest selector is "By ID". It's fast by 70%-75% than "By Class" and by 82%-87% than "By Name".

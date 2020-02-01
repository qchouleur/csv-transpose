# csv-transpose

### Introduction
A small CLI tool for CSV files to transpose column values to row values.

### How to use it

``` bash
./csv-tranpose -h

# With the provided test file
cat test.csv | ./csv-transpose -c 0 1 --title-column Equipment --value-column Value
```
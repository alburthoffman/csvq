# csvq
a simple program to query entries in CSV file

## Usage
examples
```
cat test.csv | csvq -e 'print $2 if $1 =^ "abc"'
```

## Syntax
examples
```
@define(name string, age int);print name if age >= 20 and age < 30;
```

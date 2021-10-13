# IP addressing

**177.77.77.7 - Dotted decimal notation**

```
    * this is 32 bit binary number
    * 1 set is 8 bits (4*8)
    * 8 bits is byte
    * 1 byte is 4 octet
```

## Decimal =) Binary Rules

* here is a table to get values

| position | Binary position value | Binary value
| -------- | ---------- | -------- |
| 1 | 128 |
| 2 | 64 |
| 3 | 32 |
| 4 | 16 |
| 5 | 8 |
| 6 | 4 |
| 7 | 2 |
| 8 | 1 |

```
    there are 3 rules to  change Binary <=> decimal

    1. compare `decimal number` to binary position value,if SMALLER WRITE 0 => move on to next table position #1

    2. IF IT IS EQUAL OR LARGER - minus the binary position value from your decimal number, add 1 in the binary value column

    3. move on to next position, goto #1 (with the new decimal value)
```

## Example decimal to binary

**change binary to decimal 177.77.77.7**

| position | Binary position value | Binary value
| -------- | ---------- | -------- |
| 1 | 128 | 1
| 2 | 64 | 0
| 3 | 32 | 1
| 4 | 16 | 1
| 5 | 8 | 0
| 6 | 4 | 0
| 7 | 2 | 0
| 8 | 1 | 1

## Rules :-

* `177' larger/equal than 128 (rule#2)
* 177-128=49 (new decimal number)
* add `1` in binary position

* `47` is smaller than 64
* add `0` and move on (rule#1)

* `47` is greater than 32 (rule#2)
* 47-32=17 (new decimal number)
* add `1` in binary position

* `17` is greater than 16
* 17-16=1 (new decimal number)
* add `1` in binary position

* `1` is smaller than 6,4,2
=> add `0` and move on (rule#1)

* `1` is larger/equal than 1 (rule#2)
=> add `0` and move on
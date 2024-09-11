# Data types

## Output some data

```c++
int main() {
    int var1 = 7, var2 = 3;
    printf("var1 = %d\n var2 = %i\n", var1, var2);
    // printf(layout, ...arguments separated by comma)
    return 0;
}
```

integer from -2^31 to 2^31


%i - decimal

%x - hexadecimal 

<table> 
<thead>
<td>bin</td>
<td>dec</td>
<td>hex</td>
</thead>
<tr>
<td>0 - 1 (1 bit)</td>
<td>0 - 9</td>
<td>0 - F</td>
</tr>
<tr>
<td>2 combinations</td>
<td>10 combinations</td>
<td>16 combinations</td>
</tr>
</table>

### Operations of integer:
- \+ 
- \-
- \*
- /
- %

shortcut: a += b etc

### Increment:

a++ postincrement - firstly operation - then increment
a-- postdecrement - firstly operation - then decrement

++a preincrement - firstly increment than operation
--a predecrement - firstly decrement than operation

#### Example

```c++
int main() {
    int a = 1;

    printf("a = %i\n", a++); // 1
    printf("a = %i\n", ++a); // 3

    return 0;
}
```
NOTE:
`
++a or a++ is not the same as a+1
`

**unsigned integer** diapason from 0 to 2^31 * 2 (2 times of integer)

To output unsigned - %u

#### Example:

```c++
int main() {
    unsigned a = 1;

    printf("a = %i\n", a++); // 1
    printf("a = %i\n", ++a); // 3

    return 0;
}
```

short %hi

long %li

long long %lli

Converting data types


# and.bf

This is essentially an AND gate, it tells if x and y are equal.

```
,>,

[<->-]

<[[-]-<]>

<[-]+++++++[>+++++++<-]>.

```

***',>,'*** asks for inputs. Add more commas if more than 1 digit comparisons are needed.

***'[<->-]'*** sets the second input to 0 while the first is the difference between them.

***'<[[-]-<]>'*** only runs if input two is not equal to zero, or rather if the inputs are not equal. It sets the second value to -1.

***'<[-]+++++++[>+++++++<-]>.'*** adds 49 to value two and prints. The printed value will be 48, or an ascii 0, if the previous line ran, and will be 49, ascii 1, if the previous line did not run. It will print 1 if the values are equal and 0 if they are not.
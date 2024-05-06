<H1>Almost all things to do with Matrices that I could Find</H1>

## Multiplcation of a Matrix

<H3>Rules:</H3>

A = 2x3 B = 2x3, This cannot be multiplied
But when B is transposed (B<sup>T</sup>) it becomes A = 2x3 B<sup>T</sup> = 3x2
This can be multiplied and the resultant matrix is of the size 2x2 (The remaining numbers from A = 2x3 B<sup>T</sup> = 3x2)

<H4>Given:</H4>

A =<br>
|3 4|<br>
|7 2|<br>
|5 9|

AND

B =<br>
|3 1 5|<br>
|6 9 7|

3(3) + 4(6) = 33<br>
3(1) + 4(9) = 39<br>
3(5) + 4(7) = 43<br>
7(3) + 2(6) = 33<br>
7(1) + 2(9) = 25<br>
7(5) + 2(7) = 49<br>
5(3) + 9(6) = 69<br>
5(1) + 9(9) = 86<br>
5(5) + 9(7) = 88<br>

A x B =<br>
|22 29 43|<br>
|33 25 49|<br>
|69 86 88|

## Transpose of a Matrix

<H3>Formula:</H3>

if A = i x j then A<sup>T</sup> = j x i

Where:

A<sup>T</sup> = Transpose of A<br>
i = Rows<br>
j = Columns

<H4>Given:</H4>

A =<br>
|1 3 4|<br>
|2 3 2|

A<sup>T</sup> =<br>
|1 2|<br>
|3 3|<br>
|4 2|

## Inverse of a Matrix

<H2>For a 2x2 Matrix</H2>

<H3>Formula:</H3>

A<sup>-1</sup> = 1/(ad - bc) x<br>
|d -b|<br>
|-c a|

<H4>Given:</H4>

A=<br>
|7 2|<br>
|17 5|

A<sup>-1</sup> = 1/(7(5) - 2(17)) x<br>
|5 -2|<br>
|-17 7|

A<sup>-1</sup> = 1/(35 - 34) x<br>
|5 -2|<br>
|-17 7|

A<sup>-1</sup> = 1/1 x<br>
|5 -2|<br>
|-17 5|

Therfore the inverse of matrix A is<br>
|5 -2|<br>
|-17 5|

<H4>Another Example</H4>

B=<br>
|8 6|<br>
|5 4|

B<sup>-1</sup> = 1/(8(4) - 6(5)) x<br>
|4 -6|<br>
|-5 8|

B<sup>-1</sup> = 1/(32 - 30) x<br>
|4 -6|<br>
|-5 8|

B<sup>-1</sup> = 1/(2) x<br>
|4 -6|<br>
|-5 8|

1/2 x<br>
|4 -6|<br>
|-5 8|

B<sup>-1</sup> =<br>
|2 -3|<br>
|-5/2 4|

## Determinant of a Matrix

<H2>For a 2x2 Matrix</H2>
Given:<br>
|a b|<br>
|c d|

<H3>Process:</H3>

D = ad - bc

<H2>For a 3x3 Matrix</H2>

|1 -1 -1|<br>
|2 3 8 |<br>
|-3 2 1 |

<H3>Process:</H3>

Similar to the 2x2 but with an extra step

|1 -1 -1|<br>
|2 3 8 |<br>
|-3 2 1 |

| D<sub>i j</sub> |

<H4>Where:</H4>

D = Determinant<br>
i = Row<br>
j = Column

D<sub>1 1</sub> =

|3 8 |<br>
|2 1 |

|a b|<br>
|c d|

D = ad - bc

## Cofactor of a Matrix

<H2>Formula:</H2>
C<sub>i j</sub> = (-1)<sup>i + j</sup> x | D<sub>i j</sub> |

<H3>Where:</H3>
C = Cofactor<br>
i = Row<br>
j = Column<br>
D = Determinant

<H2>Example:</H2>
Given ->

A=<br>
|1 -1 -1|<br>
|2 3 8 |<br>
|-3 2 1 |

Find C<sub>1 1</sub>

<H2>Process:</H2>

D<sub>1 1</sub>=<br>
|3 8 |<br>
|2 1 |

C<sub>1 1</sub> = (-1)<sup>1 + 1</sup> x | D<sub>i j</sub> |

C<sub>1 1</sub> = (1) (3x1 - 8x2)

C<sub>1 1</sub> = 3 - 16

C<sub>1 1</sub> = -13

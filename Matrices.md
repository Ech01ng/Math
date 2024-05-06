<H1>Almost all things to do with Matrices that I could Find</H1>

## Transpose of a Matrix

<H3>Formula:</H3>

if A = i x j then A<sup>T</sup> = j x i

Where:

A<sup>T</sup> = Transpose of A<br>
i = Rows<br>
j = Columns

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

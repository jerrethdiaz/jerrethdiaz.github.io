---
layout: project
type: project
image: img/math.png
title: "Complex Numbers in C++"
date: 2022-04-19
published: true
labels:
  - C++
summary: "A program I created in ICS 212 to compute complex math equations."
---

Math can sometimes be hard. Especially when dealing with complex and imaginary numbers. So why not make a program that can solve these problems for you. Which is what we did in our ICS 212 class. To provide an example of what it could do I included a example below:


<hr>

<pre>
This snippit of code takes two complex objects and multiplies them together to create a third complex object which stores the product of the two. So following these intital conditions:

Complex number complex1 is: (1.1 + 2.3i)
Complex number complex2 is: (-6.3 - 7.2i)
<hr>

Complex multiply(const Complex &multiplyComplex) const{
    double real3 = (real*multiplyComplex.real - imaginary*multiplyComplex.imaginary);
    double imaginary3 = (imaginary*multiplyComplex.real + real*multiplyComplex.imaginary);
    Complex complex3(real3, imaginary3);
    return complex3;
}
<hr>
This would would return in the console:

Multiply() member function. Multiply complex1 by complex2 and store it in complex3.
(9.63 - 22.41i)
Complex number complex3 is: (9.63 - 22.41i)
</pre>

<hr>

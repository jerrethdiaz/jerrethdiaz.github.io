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


Mathematics, particularly when delving into the realms of complex and imaginary numbers, can pose significant challenges. To address this complexity, we developed a program in our ICS 212 class that simplifies the process of handling these numbers. Below is an illustrative example of the program’s capability.

This particular snippet of code is designed to perform the multiplication of two complex numbers, resulting in a third complex number that represents the product. Consider the following initial conditions:

Complex number complex1 is defined as: 1.1+2.3i
Complex number complex2 is defined as: −6.3−7.2i
The function Complex multiply(const Complex &multiplyComplex) const is structured as follows:

<hr>
<pre>
Complex multiply(const Complex &multiplyComplex) const{
    double real3 = (real*multiplyComplex.real - imaginary*multiplyComplex.imaginary);
    double imaginary3 = (imaginary*multiplyComplex.real + real*multiplyComplex.imaginary);
    Complex complex3(real3, imaginary3);
    return complex3;
}
</pre>
<hr>

This would return in the console:

Multiply() member function. Multiply complex1 by complex2 and store it in complex3.
The answer was = (9.63 - 22.41i) so complex3 is: (9.63 - 22.41i). This example demonstrates the practical application of our program in simplifying complex mathematical operations, making the comprehension and manipulation of complex numbers more accessible and efficient. To view the rest of the code click [Here](https://github.com/jerrethdiaz/ImaginarynumbersinC/blob/main/diazjerreth22.cpp)

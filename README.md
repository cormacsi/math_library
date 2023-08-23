# s69_math

Implementation of your our version of the math.h library.  

## Information

C mathematical operations are a group of functions in the standard library of the C programming language implementing basic mathematical functions. All functions use floating-point numbers in one manner or another. Any functions that operate on angles use radians as the unit of angle.

### Overview of some "math.h" functions

| No. | Function | Description |
| --- | -------- | ----------- |
| 1 | `int abs(int x)` | computes absolute value of an integer value |
| 2 | `long double acos(double x)` | computes arc cosine |
| 3 | `long double asin(double x)` | computes arc sine |
| 4 | `long double atan(double x)` | computes arc tangent |
| 5 | `long double ceil(double x)` | returns the nearest integer not less than the given value |
| 6 | `long double cos(double x)` | computes cosine |
| 7 | `long double exp(double x)` | returns e raised to the given power |
| 8 | `long double fabs(double x)` | computes absolute value of a floating-point value |
| 9 | `long double floor(double x)` | returns the nearest integer not greater than the given value |
| 10 | `long double fmod(double x, double y)` | remainder of the floating-point division operation |
| 11 | `long double log(double x)` | computes natural logarithm |
| 12 | `long double pow(double base, double exp)` | raises a number to the given power |
| 13 | `long double sin(double x)` | computes sine |
| 14 | `long double sqrt(double x)` | computes square root |
| 15 | `long double tan(double x)` | computes tangent |  


## Chapter III

## Part 1. Implementing the math.h library functions

The functions of the math.h library is implemented:

- The library is developed in C language of C11 standard using gcc compiler
- The library is developed according to the principles of structured programming
- Full coverage of library functions code with unit-tests with the Check library is provided
- Unit-tests check the results of your implementation by comparing them with the implementation of the standard math.h library
- Unit tests cover 100% of each function (checked using gcov)
- Makefile for building the library and tests (with the targets all, clean, test, s21_math.a, gcov_report) is provided
- The gcov_report target generate a gcov report in the form of an html page
- The total verifiable accuracy is 16 significant digits
- Verifiable accuracy of the fractional part is up to 6 decimal places.
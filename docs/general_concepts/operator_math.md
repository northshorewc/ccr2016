---
Author: Eric Kiefer
Date: 2/17/2017
---

# Math

The type of math that is commonly used by plant staff includes basic statistics and algebra.

## Math Concepts  

All operators need to understand basic math principles. As a prerequisite, operators need to understand the following math concepts which will be discussed in this module:

* addition  
* subtraction  
* multiplication  
* division  

Operators also need to understand the following concepts:

* fractions  
* statistics  
* unit analysis  
* conversion between fractions and decimal equivalent  
* rounding  
* area  
* volume  
* rates

### Fractions  

There are many cases when operators need to work with fractions. For instance, when dealing with flow rates, operators need to remember that a flow rate such as 3.0 million gallons per day (MGD) can be written as a fraction:  

$$3.0 \frac {Million\,Gallons}{Day}$$  

This is useful to know if you are trying to add flow rates when units are not equivalent. For example, let's say you want to add 300 gallons per minute (GPM) to 3.0 MGD.  

$$300 \frac {Gallons}{Minute} + 3.0 \frac {Million\,Gallons}{Day}$$

As it is written, you cannot add these 2 fractions until you convert the units so that the units are the same. We'll come back to solving this at the very [end of the module](/general_concepts/operator_math.md#final-words).  

#### Adding and Subtracting

When the units are the same, you can proceed with basic math operations. Let's assume you are able to get the units the same, now what? Consider the following expression:

$$\frac {1}{2} + \frac{1}{4}$$

In this example, you cannot proceed until you get convert the fraction(s) so that the denominator is the same. In case you are not familiar with the term "denominator," see the following figure.

$$\frac {numerator}{denominator}$$  

Getting back to our simple example, here is how you would proceed. 

1. Multiply the numerator and denominator of one of the fractions by the same amount to get an equivalent fraction--so that the equivalent fraction has the same denominator as the other fraction.
2. Add the numerators together.
3. Note: do NOT add the demoninators!


In this case:

$$\frac {1}{2} \times \left(\frac {2}{2}\right) = \frac{2}{4}$$

$$\frac {2}{4} + \frac {1}{4} = \frac {3}{4}$$

#### Multiplying and Dividing  

When multiplying and dividing, you proceed in the following manner:  

$$\frac {a}{b} \times \frac{c}{d} = \frac {a \times c}{b \times d}$$  

$$\frac {a}{b} \div \frac{c}{d} = \frac {a}{b} \times \frac{d}{c} = \frac {a \times d}{b \times c}$$   

Using numbers instead of variable, consider the following expression:

$$\frac {2}{3} \times \frac{4}{7} = \frac {2 \times 4}{3 \times 7} = \frac {8}{21}$$

#### More Information

For more information, visit this [Khan Academy website.](https://www.khanacademy.org/math/arithmetic-home/arith-review-fractions)


### Statistics  

Statistics is a branch of mathematics dealing with the collection, analysis, interpretation, presentation, and organization of data. In applying statistics to operations, we first need to select the applicable data and the select the statistical model.

In most cases, we select all of the measurements (i.e. chlorine residual) taken over the course of the day and run the basic analyses:

* Average (mean)  
* Max  
* Min  
* Range  

#### Average

To determine the average, add up all of the values to determine the sum. Divide the sum of values by the number of samples to get the average.

For instance, let's say you have the following chlorine residuals.

$$(2.1, 2.5, 2.3, 2.7)$$

$$Sum\,of\,Values = 2.1 + 2.5 + 2.3 + 2.7 = 9.6$$

$$Number\,of\,Samples = 4$$

$$Average = \frac {Sum\,of\,Values}{Number\,of\,Samples} = \frac {9.6}{4} = 2.4$$

#### Max  

The max is the greatest value in a collection of measurements.

$$Max = 2.7$$

#### Min  

The min is the smallest value in a collection of measurements.

$$Min = 2.1$$

#### Range  

Range is the difference between the max and the min.

Use the numbers in this section:

$$Range = Max - Min = 2.7 - 2.1 = 0.6$$

### Unit Analysis  

It is important to understand units and how they apply to measurements and observations. For instance, a measurement of 2.3 ppm of free chlorine residual can be expressed as the following:

$$2.3 \frac {part}{million\,parts}$$  

or equivalently:

$$2.3 \frac {milligrams}{liter}$$  

Note: one "part" is a milligram. There are 1000 milligrams (mg) in a gram. Water weighs 1 gram (g) per milliliter. There are a thousand milliliters (mL) in a liter (L). Look at the following derivation.

$$\require{cancel}$$
$$\frac{mg}{L} = \frac{mg}{\cancel L} \times \frac{\cancel L}{1000 \cancel {mL}} \times \frac{\cancel {ml}}{\cancel g} \times \frac{\cancel g}{1000 mg}$$

$$\frac{mg}{L} = \frac {mg}{1000 \times 1000\,mg} = \frac{mg}{1,000,000 mg} = \frac {part}{million\,parts}$$  

*Note: This assumes that 1 mL equals 1 g. This is true for pure water. You can make this assumption for any chemical... just note that as you get closer to a pure chemical, this assumption fails.*  

Unit analysis is important when you need to convert units. For example, if you a pump running at 1000 gallons per minute (GPM), you need unit analysis to convert GPM to MGD.  

### Conversion Between Fractions and Decimal Equivalent  

Every fraction can be expressed as a decimal, and vice versa. For example, take the number 0.125.

$$0.125 = \frac{125}{1000} = \frac{1}{8}$$  
and take the fraction \(5/16\):  
$$\frac {5}{16} = 0.3125$$  

### Rounding  

Numbers in base 10 (the numbers we are used to using) are composed of digits that represent different values of 10. Look at the following number: 

$$124.17$$
$$\underline{hundreds}\,\underline{tens}\,\underline{ones}\,. \underline {tenths}\,\underline {hundredths}$$

* If you round to the nearest tenth, the answer is \(124.2\).  
* If you round to the nearest ten, the answer is \(120\).  
* If you round to the nearest hundred, the answer is \(100\).  

After you identify what digit you are rounding to, you look at the next digit (to the right) and determine if that number is 5 or more. If the answer is yes, then you increase the digit you are rounding to by one... and you drop all of the digits to the right. If NOT, then you don't change that digit and you drop all of the digits to the right.

### Area  

Area allows us to better describe and measure 2 dimensional shapes. For instance, the area of a rectangle is the length multiplied by width. If this rectangle represents a wall, knowing the area could tell us how much paint is required to cover it.   

[Click here for more information about area.](https://www.khanacademy.org/math/basic-geo/basic-geo-area-and-perimeter).  

### Volume  

Volume allows us to better describe and measure properties of 3 dimensional shapes. Volume is very relevant to the treatment process; we are constantly monitoring the volume of various liquids that are stored in our tanks.

In most cases, we would need to measure volume if we needed to determine how many gallons of water will fit in a rectangular chamber. In this case:

$$Volume=Length \times Width \times Height$$

To convert from volume in cubic feet to gallons, use the following conversion:

$$7.48\,gallons = 1\,cubic\,foot$$

## Final Words

Let's go back to this problem:

$$300 \frac {Gallons}{Minute} + 3.0 \frac {Million\,Gallons}{Day}$$ 

The first step is to get the units to match up.

$$300 \frac {\cancel {Gallons}}{\cancel {Minute}} \times \frac {1 Million\,Gallons}{1,000,000 \cancel {Gallons}} \times \frac {1,440 \cancel {Minutes}}{Day} =$$
$$0.432 \frac {Million\,Gallons}{Day}$$  

Then the fractions need to be added.

$$0.432 \frac {Million\,Gallons}{Day} + 3.0 \frac {Million\,Gallons}{Day} =$$

$$3.432 \frac {Million\,Gallons}{Day}$$

*Note: In Operator Chemistry we discuss significant digits. This number should be reported as 3.4 MGD if we take significant digits into consideration.

___


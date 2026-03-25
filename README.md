# Project-triangle

A Java Desktop application with a graphical user interface (GUI) that allows users to interactively check if three line segments can form a valid triangle and, if so, classifies the type of triangle formed.

## Features

* **Dynamic Adjustment:** Three independent sliders to set the lengths of segments A, B, and C (ranging from 0 to 20).
* **Mathematical Validation:** Uses the triangle inequality theorem to determine if a triangle can exist.
* **Automatic Classification:** Identifies and displays the type of triangle:
  * **Equilateral:** All sides are equal.
  * **Isosceles:** Two sides are equal.
  * **Scalene:** All sides are different.
* **Responsive Interface:** Segment values are updated on the screen in real-time as the sliders are moved. The result panel remains hidden until the verification is triggered.

## Technologies Used

* **Language:** Java
* **Graphical Interface:** Java Swing
* **Recommended IDE:** Apache NetBeans

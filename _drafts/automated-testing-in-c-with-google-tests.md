---
title: "Automated testing in C++ with Google Tests."
excerpt: "Explore the automation of testing in C++ using google tests and google mock."

show_hero: false

categories:
  - Learn

tags:
  - C++
  - Testing
  - Automation
  - GoogleTests
  - GoogleMocks
---

The goal of testing is to verify the correct working of an application.

## Types of testing

1. Unit testing
2. Integration testing
3. Acceptance testing

As developers we perform only unit testing and integration testing.
Unit testing is to isolate a block of code and test it,
Integration testing is for checking the correctness of the application.

## Grouping test suites

The tests are grouped as:

1. Functional tests - to check the working of the application for any given input.
2. Error handling tests - to check error handling of the application for an error input.
3. Input combination tests - to check the behavior and correctness of the application for all possible inputs.
4. Boundary tests - to verify the edge cases and limits of the applications.
5. Performance tests - to verify time and space requirements of the application code.

## Block diagram

![Automated unit testing Block Diagram][BlockDiagram]

[BlockDiagram]: {{ '/assets/images/' | relative_url |  append: "/post_cpp_auto_testing/automated_unit_testing_block_diagram.jpg" }}
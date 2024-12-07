# Scala NullPointerException Bug

This repository demonstrates a simple Scala program that throws a `NullPointerException` under certain conditions.

## Bug Description

A `NullPointerException` is thrown when attempting to create an instance of `MyClass` with a `null` value for the `name` parameter.  This occurs because the class doesn't handle null input gracefully.

## Bug Reproduction

1. Clone this repository.
2. Compile and run `Main.scala`.
3. Observe the `NullPointerException` during the creation of `anotherPerson`.

## Solution

The solution involves adding null checks or using an Option to handle potential null values, making the class more robust.
# Sintax direct translation: Boolean Calculator

## Abstract
Design of a grammar and his implementation using a top-down/ bottom-top analyzer/translator that represent a boolean calculator using python.

### Introduction

The boolean calculator allow this operations represented by the examples of this table:

| Input                           | Output          |
|---------------------------------|-----------------|
| x := true;                      |                 |
| print x;                        | The result is 1 |
| y := false and x;               |                 |
| print not y;                    | The result is 1 |
| print x and not y;              | The result is 1 |
| print not (x and not y);        | The result is 0 |
| x := not x;                     |                 |
| z := true or not (x and not y); |                 |

- There are `Id's ` 
- There are `or`  binary and left asociative.
- There are `and` and is binary and left asociative and more priority than the `or` operator.
- There are asign operator `:=`
- There are print sentence `print *values*`
- There are `True` and `False` constants.
- There are `()`


## Methodology

### Stage : 1

Design the grammar for a bottom-top translator with his translation scheme.

### Stage: 2

Adapt the grammar for a top-bottom translator.

### Stage: 3

Add the translation scheme to stage 2

### Stage: 4

Implement the top-bottom recursive translator resuling from stage 3 using *Python*.
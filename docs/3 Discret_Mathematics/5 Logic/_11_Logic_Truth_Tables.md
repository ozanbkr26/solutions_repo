# Problem 11 – Logic: Truth Tables & Propositions

## Problem Statement

Analyze the truth values of compound propositions involving **AND**, **OR**, and **NOT**.  
Evaluate the truth table for:  
`(p ∧ ¬q) ∨ r`

## Given:

- p, q, r ∈ {True, False}

## Truth Table:

| p     | q     | r     | ¬q    | p ∧ ¬q | (p ∧ ¬q) ∨ r |
|-------|-------|-------|-------|--------|--------------|
| True  | True  | True  | False | False  | True         |
| True  | True  | False | False | False  | False        |
| True  | False | True  | True  | True   | True         |
| True  | False | False | True  | True   | True         |
| False | True  | True  | False | False  | True         |
| False | True  | False | False | False  | False        |
| False | False | True  | True  | False  | True         |
| False | False | False | True  | False  | False        |

## Visualization

Below is a truth table showing all logical combinations:

![Logic Table](_pics/logic_table.png)

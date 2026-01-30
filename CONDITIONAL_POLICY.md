# Conditional Policy (Repository Rule)

## Status labels
A result is **Conditional** iff its proof uses any item listed as an unproven axiom/principle/conjecture in this repository (including XYSTEM).

## Mandatory labeling rule
Any statement whose derivation depends on XYSTEM must be labeled exactly:

**Conditional (Assuming XYSTEM).**

Equivalently, in LaTeX, use a title suffix:
\[
(\text{Conditional: Assuming XYSTEM})
\]
or an environment header:
\begin{theorem}[Conditional (Assuming XYSTEM)]
...

## Dependency disclosure
Each Conditional result must include a dependency list containing the token:
- XYSTEM

## Prohibition
No theorem depending on XYSTEM may be stated without the Conditional label.

## File placement
Unproven principles live under `axioms/` with:
- a short `Status: Conditional (Unproven)` header, and
- a single boxed formal statement.

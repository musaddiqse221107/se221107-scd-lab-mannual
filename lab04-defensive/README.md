# Lab 4 — Defensive Programming
Boundary validation rejects invalid quantities. Domain exceptions distinguish invalid orders from insufficient stock, while an assertion protects the internal non-negative-stock invariant.
Hierarchy: RuntimeException -> OrderException -> InvalidOrderException / InsufficientStockException.
Tests intentionally trigger each exception path.
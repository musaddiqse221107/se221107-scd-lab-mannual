# TDD Log
Cycle 1 red: single-price test; green: gateway result; refactor: PricingGateway.
Cycle 2 red: quantity-10 test; green: discount; refactor: finalPrice.
Cycle 3 red: zero-quantity test; green: validation; refactor: boundary check.
The dependency is mocked because it represents an external pricing boundary.
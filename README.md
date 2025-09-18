# Market

## Overview
Market is a C++ console application simulating a retail transaction system. It models key components of a point-of-sale environment including cash registers, cards, items, inventory management, tax calculations, and receipt generation. The design emphasizes modularity and object-oriented principles.

## Features
- Detects card types for payments: Amex, Visa, MasterCard, Discover.
- Manages inventory and individual items.
- Generates receipts for transactions.
- Calculates applicable taxes.
- Modular architecture with clear separation of functionality.

## File Summary
- `CashRegister.cpp`: Manages transaction processing.
- `ReceiptGenerator.cpp`: Contains main function demonstrating card type detection.
- `card.cpp` / `card.h`: Implements payment card logic.
- `inventory.cpp` / `inventory.h`: Manages product inventory data.
- `item.cpp` / `item.h`: Defines item properties and behaviors.
- `market.cpp` / `market.h`: Core market operations.
- `receipt.cpp` / `receipt.h`: Receipt management.
- `tax.cpp` / `tax.h`: Handles tax computations.

## Contributors
- Joseph Guzman
- Evan Nguyen

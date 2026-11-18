# E-Commerce Shopping Cart System in C

A menu-driven console e-commerce application written in C that demonstrates structures, pointers, and dynamic memory management.

## Features
- **Product Catalogue:** Displays 6 pre-loaded electronics items with ID, price, and live stock availability.
- **Dynamic Shopping Cart:** Uses `realloc()` and `free()` to grow and shrink the cart dynamically at runtime.
- **Stock Validation:** Prevents adding quantities exceeding available inventory and updates quantities for existing cart items.
- **Automated Discount Slabs:**
  - **15% off** on orders of ₹50,000 and above
  - **10% off** on orders of ₹10,000 and above
  - **5% off** on orders of ₹2,000 and above
- **Checkout & Billing:** Generates an itemized bill, deducts purchased quantities from stock, and frees cart memory.
- **Safe Input Handling:** Clears invalid non-integer inputs to prevent infinite loops.

## Core C Concepts Used
- Structures (`struct`) & Array of Structures
- Pointers & Double Pointers (`CartItem **`)
- Dynamic Memory Allocation (`realloc`, `free`)
- Modular Functions & Switch-Case Menu Control

## How to Compile & Run

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>

// ==========================================================
// Task 1: E-Commerce Shopping Cart System
// ==========================================================

// Scenario:
// You are developing an Online Shopping Cart System for an e-commerce application.
// The system should calculate the final bill based on product details,
// discounts, taxes, and delivery eligibility.


// Requirements:

//  Store customer information.
//    - Customer Name
//    - Customer ID
//    - Membership Type (Silver, Gold, Platinum)

//  Store product information.
//    - Product Name
//    - Product Category
//    - Product Price
//    - Quantity Purchased
//    - Product Stock Availability

//  Calculate the following.
//    - Subtotal
//    - Product Discount
//    - GST Amount
//    - Final Bill Amount

//  Apply discount based on Membership Type.
//    - Platinum → 20%
//    - Gold → 15%
//    - Silver → 10%
//    - Regular → No Discount

//  Validate Coupon Code.
//    - If the coupon is valid,
//      apply an additional discount.
//    - Otherwise,
//      continue without a coupon discount.

//  Check Free Delivery Eligibility.
//    - Final Bill ≥ ₹2000
//      → Free Delivery
//    - Otherwise
//      → Delivery Charge ₹150

//  Check Product Availability.
//    - If Stock > 0
//      → Continue Purchase
//    - Otherwise
//      → Out of Stock

//  Generate a complete invoice displaying.
//    - Customer Details
//    - Product Details
//    - Membership Type
//    - Discount Amount
//    - GST Amount
//    - Delivery Charge
//    - Final Payable Amount
//    - Order Status


// Concepts Used:

//  Variables
//    Store customer, product, and billing information.

//  Primitive Data Types
//    Use string, number, and boolean values.

//  Non-Primitive Data Types
//    Store multiple product details using objects or arrays.

//  Type Inference
//    Automatically infer variable types.

//  Type Assertion
//    Convert values to the required data type.

//  Template Literals
//    Display the invoice in a formatted output.

//  Arithmetic Operators
//    Calculate subtotal, discount, GST, and final amount.

//  Assignment Operators
//    Update bill amounts after each calculation.

//  Comparison Operators
//    Check stock availability, minimum purchase, and delivery eligibility.

//  Logical Operators
//    Validate coupon code and membership conditions.

//  Unary Operators
//    Increase or decrease product quantity.

//  Ternary Operator
//    Determine Free Delivery or Delivery Charge.

//  if
//    Validate product availability.

//  if...else
//    Check coupon validity.

//  else if
//    Apply membership-based discounts.

//  Nested if
//    Validate stock first, then apply coupon.

//  switch
//    Display discount based on Membership Type.
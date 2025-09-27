# FUNCTIONAL REQUIREMENTS:

The system shall allow a user to view a list of products with id, name, price, add or remove items, and see available_qty.

the system shall allow users to place one order with one orr more products.

The order service shall check stock item levels in the inventory before comfirming an order.

The front-end shall display the final order status success, pending or failed.

Update inventory and display the items remeining tto the user.

User shall view all added and ready to purchase items in a shopping-cart where they will confirm all purchases.

# FUNCTIONAL REQUIREMENT:

Each service must expose `GET /healthz` returning HTTP 200 within 300 ms.

- The checkout flow (browse → order → pay) must complete in under 2 seconds locally.
- The system must run using a single command: `docker compose up`.
- All logs must include `timestamp`, `level`, and `msg` in JSON format.

# Notes of Professor Harrison's Office Hours Advice


Regarding the shopping cart microservice:
This microservice has two tables
A cart, and an item table.
An item is in a cart.
One cart, multiple items.

Every item is an instance of some product somewhere else
UUIDs

Count in items table
Shopping Cart might contain "n" items.
How many you have of each item.

Could make this part of main app. Doesn't have to be a microservice.
It can be if we want.

Anything consumed by main, admin, and mod, must be a microservice.

For any piece of data should be held in one database in a single microservice.

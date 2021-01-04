# Race-condtion-notes

############## Summary and techniques For Race Condition ##########################


Mindset:

  Watch For the situation where your action depends on a condition,
  Look for any action that seems to execute a database lookup, apply Application Logic and update database.

Common Back end practises:

1) Lookup records and then acting on records.

2) Update in records, create a delay between the condition and action that modifies the condition.


Different Case Studies:

1) Bypassing Invite send Limit.
2) Gift Card Discount
3) Redeem coupon
4) Mutiple Payments
5) Add single email multiple times
6) Upvote / Follow user multiple times
7) Transfer data/money/ gifts multiple times
8) Invite Link send multiple times > Bypass limit


Reference:
* Medium
* Real world bug huning Book

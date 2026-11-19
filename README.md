# Cribalicious

**Live demo: https://aquarius4310.github.io/Cribalicous/**

A clickable demo of Cribalicious, a baby gear rental business for new parents in Washington, DC. Built for an AP Business class project. Nothing is real: no accounts, payments or deliveries.

## What you can click through

1. **Home** with the featured Newborn Bundle ($490 for 6 months vs. $1,810 new)
2. **Gear catalog** with filters
3. **Item page** with a rental-length slider showing total price, price per month and savings vs. buying new
4. **Cart** with the delivery rule
5. **Checkout** with a DC address (non-DC ZIPs are rejected) and a delivery date
6. **Order confirmation**
7. **My rentals** where you can extend, return or swap for the next stage

## Pricing rules in the demo

- Prices come from the team's pricing research.
- A customer never pays more than 60% of the new price. At the cap, the item is theirs to keep.
- Delivery is $25 each way for rentals under 3 months, and free at 3+ months or on orders over $150.
- Cribs and Pack 'n Plays are short-term only. No car seats.

## Changing prices

All prices are in one block near the top of the `<script>` in `index.html` (`TIERS`, `CAP`, `DELIVERY` and `GEAR`). Edit the numbers and the whole site updates.

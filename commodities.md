#Commodities in Space Sim
----

1. Each planet (spob) has a techlevel (`T`)
2. Each commodity has a minimum techlevel (`M`). If `T` ≤ `M`, the commodity is available to be purchased/sold
3. Each commodity has a base price (`B`)
4. Commodity pricing (`P` (per ton)) is inversely proportional to `T` (ie: The greater the difference between `T` and `M`, `P` will be cheaper). `P = B * (M/T)`.
5. Let's take that one step further. Each spob has a supply (`S`) of a commodity available (where `T` ≤ `M`, of course). So now, `P = ((B * (M/T)) / S) * 1000`
6. Players can affect the price of commodities by moving them from one spob to another.

#Commodity manufacturing
----

Given a high enough skill level (option A), or enough money to purchase the ability (option B), players can purhcase commodities and combine them to create new commodities that aren't normally available. The current examples are below: 

![alt text](https://raw.github.com/nfreader/Space-Sim-Docs/master/manufacturing.png)

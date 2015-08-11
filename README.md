# Snacks

A fast food store has asked you to build an online ordering system. An order is input as a single string that 
mixes single digit numbers and snack ids in any order, such as
    b2fc = burger, 2 fries, coke
    fbfc = burger, 2 fries, coke
The snacks are identified by the first character of the name. They are in three groups; the groups and cost per serve 
are shown below. The kitchen has 3 of each snack in stock, so they may run out of a snack. If there are not enough serves
of a snack left to fill the order, ask the customer if they want to substitute a similar snack (a snack in the same group); 
repeat as needed. When an order has been filled, show the filled order and the cost.

  Main meal
    burger, $3.45
    wrap, $4.32
  Sides
    fries, $4.20
    muffin, $2.50
    hashBrown, $4.32
  Drinks
    coke, $1.23
    koffee, $2.34
    slurpee, $3.45
    tea, $4.56
    juice, $5.67
    
The menu has 6 choices; a choice is a single character input:
• o: order
• z: zet (set) favourite order
• u: use favourite order
• s: show the stock left
• f: exit the menu and store to file
• x: exit the menu
• anything else: help

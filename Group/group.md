# Second Price Sealed Bid Auctions
Second price sealed bid auctions are similar to the previous example but as the name
suggests have a key difference, the winner of the auction only pays the second highest
bid. This sounds counter-intuitive however if you've ever used E-Bay before then you
have participated in such an auction, with the only difference being you can see the
current winning bid. This type of auction has a very nice property in that truth-telling
is a dominant strategy, this means that always bidding the amount that you personally value
the item at is always the best strategy for you regardless of whether other players over or
under bid. Such a property makes this a very nice and fair kind of auction to partake in
as no one can gain an advantage over anyone else by employing a complex strategy. This also
produces a very clean and simple pure nash equilibrium in which all players bid their valuations
as since every players action is dominant then this must be a nash equilibrium as any other bid
will give a payoff less than or equal to bidding the valuation.

# Questions:

## **Could you expand on why truthulness is a dominant strategy and a nash equilibrium**
Of course! This hinges on the fact that the amount the winner bids does not dictate how much
money they spend and their payoff, that is decided by the highest bid of the other players.
As we assume all other players bids remain the same when player *i* deviates from their bid
such a bid b' can only change whether a player wins or loses not their payoff. So if player i
were to increase their bid from their valuation then this can only affect the payoff if it
changes the outcome of the auction. The same is true if they decrease to below the evaluation.

- **Case 1 Change from lose to win by increasing:** For this to be the case the new bid must be
greater than the current greatest bid. This current greatest bid must be greater than player i's
evaluation therefore if player i's new bid is the new greatest bid then the paid price will be the
old one resulting in a negative payoff thus being worse than bidding the valuation.

- **Case 2 Change from win to lose by decreasing:** For this to happen the new bid must become a
losing bid so at least one bid $b_j$ must now be greater than player i's new bid. Since player i's
original bid was their valuation and $b_j$ was the second highest bid at the time and was less than
the valuation then their original payoff was $v_i - b_j$ and since $b_j < v_i$ then the payoff was
greater than 0, however now since they are now losing the auction it is 0 hence no improvement.

## **You mentioned a nash equilibrium when players bid truthully, are there any more?**
Yes in fact this particular type of auction has many different nash equilibria another example
is if player 1 bids their valuation and all other players bid 0. In this case if player 1 were to
increase their bid then they would still win the item at the same price of 0 so a payoff of $v_{1}-0$. 
If any other player were to increase their valuation then it is either stillless than player 1's bid
and their payoff is still 0 so no improvement. Or their bid is greater than player 1's and since
their valuation is higher than player 1's then they will have to pay more than their valuation and
obtain a negative payoff which is clearly worse than 0.

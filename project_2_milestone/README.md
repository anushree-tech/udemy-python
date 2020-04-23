## Black Jack Game

### Introduction : 
Black jack is card game which is mostly played in casino, we will be playing a simplified version of this game.
Value of cards 2-10 : 10
              J,Q,K : 10
                  A : 1 or 11
To win we have to get sum of all cards as close to 21.

### Description:

**Class**

1. Card : It has attributes suit and rank
2. Deck : Produce a deck of cards,shuffle and deal
3. Hand : Add card and adjust for ace
4. chips : total chips and bet

**functions**

1. take_bet() : function for taking bets
2. hit() : function for taking hits. Add card in players hand from the deck.
3. hit_or_stand(): Ask user to hit(add card) or stand(stop adding cards)
4. show_some(): shows player all cards and dealers all card except one hidden card
5. show_all(): show all cards of player and dealer including dealer's hidden card
6. player_busts(): Player value is above 21
7. player_wins(): Player wins
8. dealer_bursts(): Dealer value is above 21
9. dealer_wins():  Dealer wins
10 push(): Tie b/w dealer and player

### Game Steps:

To play a hand of Blackjack the following steps must be followed:
1. Create a deck of 52 cards
2. Shuffle the deck
3. Ask the Player for their bet
4. Make sure that the Player's bet does not exceed their available chips
5. Deal two cards to the Dealer and two cards to the Player
6. Show only one of the Dealer's cards, the other remains hidden
7. Show both of the Player's cards
8. Ask the Player if they wish to Hit, and take another card
9. If the Player's hand doesn't Bust (go over 21), ask if they'd like to Hit again.
10. If a Player Stands, play the Dealer's hand. The dealer will always Hit until the Dealer's value meets or exceeds 17
11. Determine the winner and adjust the Player's chips accordingly
12. Ask the Player if they'd like to play again

    

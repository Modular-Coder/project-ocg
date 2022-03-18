# project-ocg
A weighted card game for everyone.

# The problem
The popular trading card games of our time are:
- expensive 
- lack self-balancing
- constrained by sets
- based heavily on RNG (IE: resource constraints)
- are owned by large companies not focused soley on competitive play

# The Solution
An open source card game with:
- All cards free to everyone
- Free to play
- Create and/or share your own cards/decks
- Self-balancing
  - cards are made of abilities with weighted scores
  - cards have different score limits
  - these score limits dictate the cards tier (1, 2, 3, 4, 5)
  - formats are based on the number of each tier card in a deck (IE: standard may have 10 Tier 1,  10 Tier 2, 10 Tier 3, etc... )
  - periodic re-balancing of weights based on real tournament data throughout a season

# The game
Initial ideas
- Life total for a player is 30
- Avatar 
  - sets resource amount (doesn't grow overtime start with full) 
  - effects the field, 
  - may have abilities
- No turns
- Each player gets priority queues cards face down up to their resource value (backs of cards show value)
- Cards are flipped
- Attacks and blocks of units happen
- then cards flip and resolve at the same time
- some cards may allow flip early
- if unit isn't blocked damage goes to opposing player
- otherwise it goes to the creature it is blocked by
- players may choose not to block
- cards may deal damage or heal damage directly to a player or unit
- 
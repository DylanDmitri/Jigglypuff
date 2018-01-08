# Jigglypuff
Pokémon Showdown Randombattle AI

## for settup, we need 

- A pokémon showdown server instance
-- clone from git
-- run somewhere? google cloud?

- An API wrapper around the server
-- give a clear presentation of battlestate (weather, pokemon, hp, statuses, moves, type/damage of moves)
-- so that we choose ```flareon - flare blitz``` rather than ```move 3```

- a 'battle' function between two entities
-- create random battle on server
-- connect players
-- until battle is over
--- both players see battle state and options
--- both players make choices
--- both players see other's choice

## after that

we explore different learning algorithms

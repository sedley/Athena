Athena
======

Athena is a plugin for source mod which monitors the live gamestate of a counter-strike source server,
and updates an online scoreboard accordingly.  Because we can not pull scores from the game, scores are first
initalized as local vars ct_score and t_score starting at 0.  When we detect that a team has won, we inc those 
vars in line with the in game scores, creating a remote view of the gamestate.
